---
title: Zprávy odeslané skupině Microsoft 365 nedostávají všichni členové.
ms.author: pebaum
author: pebaum
manager: mnirkhe
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003200"
- "5995"
ms.openlocfilehash: 080c060f5675065704c7209bd15e4cbb1236b8db
ms.sourcegitcommit: b71e5981b7f30ef2bce4e695118d03aa68a5be4a
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/05/2021
ms.locfileid: "50480676"
---
# <a name="messages-sent-to-a-microsoft-365-group-are-not-received-by-all-members"></a>Zprávy odeslané skupině Microsoft 365 nedostávají všichni členové.

Ujistěte se, že se všichni členové skupiny přihlásili k odběru e-mailů. Podívejte se na článek [Sledování skupiny v Outlooku](https://support.microsoft.com/office/e147fc19-f548-4cd2-834f-80c6235b7c36).  

Pokud chcete zkontrolovat stav zpráv členů, kteří se přihlásili k odběru e-mailů skupiny, spusťte následující příkaz v prostředí [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps&preserve-view=true):

`Get-UnifiedGroup <GroupName> | Get-UnifiedGroupLinks -LinkType Subscribers`

Pomocí následujícího příkazu v prostředí EXO PowerShell nakonfigurujte všechny členy skupiny tak, aby dostávali do doručené pošty e-maily odeslané skupině Microsoft 365:

`$Group = "Address of [Microsoft 365 Groups]"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`

Například:

`$Group = "testg@contoso.onmicrosoft.com"Get-UnifiedGroupLinks $Group -LinkType Member | % {Add-UnifiedGroupLinks -Identity $Group -LinkType subscriber -Links $_.Guid.toString() -Confirm:$false}`
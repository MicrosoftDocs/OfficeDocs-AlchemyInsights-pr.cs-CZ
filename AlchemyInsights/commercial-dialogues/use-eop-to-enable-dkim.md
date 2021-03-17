---
title: Povolení funkce DKIM pro konkrétní doménu pomocí Exchange Online PowerShellu
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/23/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002531"
- "7375"
ms.openlocfilehash: 2f2b60a63b512bde794ba588852db11423e766f3
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744650"
---
# <a name="use-exchange-online-powershell-to-enable-dkim-for-a-specific-domain"></a><span data-ttu-id="279e6-102">Povolení funkce DKIM pro konkrétní doménu pomocí Exchange Online PowerShellu</span><span class="sxs-lookup"><span data-stu-id="279e6-102">Use Exchange Online PowerShell to enable DKIM for a specific domain</span></span>

<span data-ttu-id="279e6-103">Pokud nemůžete vytvořit záznamy DNS DKIM v Centru pro správu, zkuste použít Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="279e6-103">If you can't create the DKIM DNS records in the admin center, try using Exchange Online PowerShell.</span></span> 

<span data-ttu-id="279e6-104">Pokud chcete vytvořit záznam DNS DKIM pomocí Exchange Online PowerShellu, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="279e6-104">To create a DKIM DNS record using Exchange Online PowerShell, perform the following steps:</span></span>

1. <span data-ttu-id="279e6-105">Otevřete Windows PowerShell jako správce a v popsaném pořadí spusťte následující příkazy:</span><span class="sxs-lookup"><span data-stu-id="279e6-105">Open Windows PowerShell as an administrator and run the following commands in the described sequence:</span></span>

    <span data-ttu-id="279e6-106">a.</span><span class="sxs-lookup"><span data-stu-id="279e6-106">a.</span></span> `$UserCredential = Get-Credential`

    <span data-ttu-id="279e6-107">b.</span><span class="sxs-lookup"><span data-stu-id="279e6-107">b.</span></span> `$Session = New-PSSession -ConfigurationName Microsoft.Exchange -ConnectionUri https://outlook.office365.com/powershell-liveid/ -Credential $UserCredential -Authentication Basic -AllowRedirection`

    <span data-ttu-id="279e6-108">c.</span><span class="sxs-lookup"><span data-stu-id="279e6-108">c.</span></span> `Import-PSSession $Session -DisableNameChecking`
    
<span data-ttu-id="279e6-109">Pokud máte potíže s připojením k Exchange Online PowerShellu, podívejte se na stránku [Připojení k Exchange Online PowerShellu.](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell)</span><span class="sxs-lookup"><span data-stu-id="279e6-109">If you have trouble connecting to Exchange Online PowerShell, see [Connect to Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="279e6-110">Až budete připojení k Exchange Online PowerShellu, spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="279e6-110">Once you're connected to Exchange Online PowerShell, run the following command:</span></span>

    `New-DkimSigningConfig -DomainName < CustomDomain > -Enabled $true`

3. <span data-ttu-id="279e6-111">Po úspěšném spuštění výše uvedeného příkazu ukončete relaci Exchange Online PowerShellu spuštěním následujícího příkazu:</span><span class="sxs-lookup"><span data-stu-id="279e6-111">Once the above command has been successfully executed, run the following command to terminate the Exchange Online PowerShell session:</span></span>

    `Remove-PSSession $Session` 



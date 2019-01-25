---
title: Přesunutí e-mailové zprávy do poštovní schránky archiv
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 41d6825b568263fb7b09066b65235aa348415bae
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29462985"
---
Dochází k potížím, archivaci položek poštovní schránky archiv. Ujistěte se, zda že jste provedli následující kroky:
  
1. Potvrďte, že **Archivovat poštovní schránky** je povoleno. Pokud tomu tak není, pomocí kroků v [tomto článku](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) povolení archivační poštovní schránky. 
    
2. Ve středisku pro správce serveru Exchange vyberte **Značky uchovávání informací** v části **Správa kompatibility**, vytvořte **značku uchovávání informací** pomocí akce **přesunout do archivu** obsahující požadované **Stáří uchovávání informací**.
    
3. Ve středisku pro správce serveru Exchange vyberte **Zásady uchovávání informací**, vytvořit **Zásady uchovávání informací** a přidat tuto zásadu uchovávání tag **přesunout do archivu** . 
    
4. [Přiřazení zásady uchovávání informací](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) poštovní schránky konkrétního uživatele. Stejná zásada se použije **primární** a **archivační** poštovní schránky. 
    
Poštovní schránka uživatele by měl mít nyní zásad archivace přesunout položky do poštovní schránky archiv. Může být nutné vynutit spravované složky pomocníka (MFA) spustit a použít nové nastavení poštovní schránky uživatele. Spusťte následující příkaz při [připojeni k EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) ke spuštění spravované složky Pomocníka pro určité poštovní schránky: 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

Další informace o nastavení zásad archivace, viz [nastavit zásady archivace a odstranění poštovních schránek](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  


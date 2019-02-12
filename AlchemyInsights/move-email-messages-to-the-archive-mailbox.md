---
title: Přesunutí e-mailové zprávy do poštovní schránky archiv
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: a631af20e28a531a40f078e290239a372c38ab74
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29941695"
---
<span data-ttu-id="0f56b-p101">Dochází k potížím, archivaci položek poštovní schránky archiv. Ujistěte se, zda že jste provedli následující kroky:</span><span class="sxs-lookup"><span data-stu-id="0f56b-p101">Having problems archiving items to the Archive mailbox. Make sure you have performed the following steps:</span></span>
  
1. <span data-ttu-id="0f56b-p102">Potvrďte, že **Archivovat poštovní schránky** je povoleno. Pokud tomu tak není, pomocí kroků v [tomto článku](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) povolení archivační poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="0f56b-p102">Confirm that an **Archive mailbox** has been enabled. If not, use steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span> 
    
2. <span data-ttu-id="0f56b-106">Ve středisku pro správce serveru Exchange vyberte **Značky uchovávání informací** v části **Správa kompatibility**, vytvořte **značku uchovávání informací** pomocí akce **přesunout do archivu** obsahující požadované **Stáří uchovávání informací**.</span><span class="sxs-lookup"><span data-stu-id="0f56b-106">In the Exchange Admin Center, select **Retention Tags** under **Compliance Management**, create a **Retention tag** with the **Move to Archive** action containing the desired **Retention Age**.</span></span>
    
3. <span data-ttu-id="0f56b-107">Ve středisku pro správce serveru Exchange vyberte **Zásady uchovávání informací**, vytvořit **Zásady uchovávání informací** a přidat tuto zásadu uchovávání tag **přesunout do archivu** .</span><span class="sxs-lookup"><span data-stu-id="0f56b-107">In the Exchange Admin Center, select **Retention Policies**, create a **Retention Policy** and add your **Move to Archive** retention tag to that policy.</span></span> 
    
4. <span data-ttu-id="0f56b-p103">[Přiřazení zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) poštovní schránky konkrétního uživatele. Stejná zásada se použije **primární** a **archivační** poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="0f56b-p103">[Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox. The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span> 
    
<span data-ttu-id="0f56b-p104">Poštovní schránka uživatele by měl mít nyní zásad archivace přesunout položky do poštovní schránky archiv. Může být nutné vynutit spravované složky pomocníka (MFA) spustit a použít nové nastavení poštovní schránky uživatele. Spusťte následující příkaz při [připojeni k EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) ke spuštění spravované složky Pomocníka pro určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="0f56b-p104">The user's mailbox should now have an Archive policy to move items to the Archive mailbox. It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox. Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span> 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

<span data-ttu-id="0f56b-113">Další informace o nastavení zásad archivace, viz [nastavit zásady archivace a odstranění poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="0f56b-113">Want more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  


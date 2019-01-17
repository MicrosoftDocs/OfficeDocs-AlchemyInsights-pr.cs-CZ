---
title: Složka RecoverableItems. 1336 je plná.
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: ee96abfa179c36ebaf43dbd327d4608b849395d3
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281366"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="2b850-102">Složka obnovitelné položky je plná.</span><span class="sxs-lookup"><span data-stu-id="2b850-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="2b850-p101">Výchozí limit úložiště pro složku obnovitelné položky pro Exchange Online poštovní schránky ve službách Office 365, je 30 GB. Omezení úložiště pro složku obnovitelné položky se automaticky zvýší na 100 GB, pokud poštovní schránka je umístěna na soudní spory podržte služba eDiscovery blokování nebo je přiřazena zásadám uchovávání informací služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="2b850-p101">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB. The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="2b850-105">Pokud se složky obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky bude ovlivněna následujícími způsoby:</span><span class="sxs-lookup"><span data-stu-id="2b850-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="2b850-106">Uživatele nelze odstranit položky z poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="2b850-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="2b850-107">Spravované složky pomocníka nelze odstranit položky založené na značku uchovávání informací nebo nastavení spravované složky.</span><span class="sxs-lookup"><span data-stu-id="2b850-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="2b850-108">Poštovní schránky, které mají jeden obnovení položky povoleno nebo jsou blokována nelze udržovat proces ochrana stránky kopírování při zápisu verze položek upraven uživatelem.</span><span class="sxs-lookup"><span data-stu-id="2b850-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="2b850-109">Pro poštovní schránky, které mají povoleno protokolování auditování poštovní schránky mohou být uloženy žádné položky protokolu auditování poštovní schránky ve audity podsložky ve složce obnovitelných položek.</span><span class="sxs-lookup"><span data-stu-id="2b850-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="2b850-p102">Pro poštovní schránky, které nejsou blokována, můžete použít admins `Search-Mailbox -SearchDumpsterOnly -DeleteContent` příkazu v Exchange Online PowerShell, chcete-li odstranit položky ve složce obnovitelné položky. Další informace naleznete v následujících tématech:</span><span class="sxs-lookup"><span data-stu-id="2b850-p102">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder. For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="2b850-112">Vyhledání a odstranění zpráv</span><span class="sxs-lookup"><span data-stu-id="2b850-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="2b850-113">Hledání-poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="2b850-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="2b850-p103">Pro poštovní schránky, které jsou blokovány admins před nutné odebrat blokování mohou odstraněné položky ze složky obnovitelné položky. Další informace naleznete v tématu [Odstranění položek v obnovitelných položek, stiskněte a podržte složku cloudové poštovní schránky na](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="2b850-p103">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder. For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="2b850-p104">Zabránit složky obnovitelné položky stále plné, admins můžete zvýšit limit velikosti obnovitelných položek složky pro poštovní schránky na uložení a nastavit zásady uchovávání informací poštovní schránky, který přesune položky ze složky obnovitelné položky do archivu uživatele poštovní schránka. Viz [zvýšení obnovitelných položek kvóty poštovní schránky na uložení](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="2b850-p104">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox. See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  

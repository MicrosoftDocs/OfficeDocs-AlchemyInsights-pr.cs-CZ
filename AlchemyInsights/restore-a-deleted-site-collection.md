---
title: Obnovení odstraněného webu
ms.author: kaarins
author: kaarins
manager: scotv
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: a1fb15869b9f576696de4eda4c0b2101bd6cca17
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768541"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="cd0c9-102">Obnovení odstraněného webu</span><span class="sxs-lookup"><span data-stu-id="cd0c9-102">Restore a deleted site</span></span>

<span data-ttu-id="cd0c9-103">Pokud správce odstraní web služby SharePoint, umístí jej do koše kolekce webů, kde je uchováván po dobu 93 dní před trvalým odstraněním.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-103">When an admin deletes a SharePoint site, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="cd0c9-104">Obnovení webu:</span><span class="sxs-lookup"><span data-stu-id="cd0c9-104">To restore the site:</span></span>
  
1. <span data-ttu-id="cd0c9-105">V novém centru pro správu služby SharePoint klepněte na tlačítko **Koš** na pásu karet.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="cd0c9-106">Zaškrtněte políčko vedle kolekce webů, kterou chcete obnovit.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="cd0c9-107">Klepněte na tlačítko **Obnovit odstraněné položky**.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="cd0c9-108">Chcete-li obnovit odstraněný komunikační web, můžete použít nové centrum pro správu služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="cd0c9-109">V opačném případě je nutné použít prostředí Microsoft PowerShell.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="cd0c9-110">Chcete-li obnovit web, který patří do skupiny Office 365, je třeba obnovit skupinu v centru pro správu serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="cd0c9-111">Skupiny lze obnovit po dobu 30 dní po odstranění.</span><span class="sxs-lookup"><span data-stu-id="cd0c9-111">Groups can be restored for 30 days after they're deleted.</span></span>
  


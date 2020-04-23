---
title: Sdílení s externími uživateli nefunguje
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 285535d6144825f0935bf72579a483260c2f2bd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767242"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="54a74-102">Řešení problémů se sdílením sharepointového obsahu s externími uživateli</span><span class="sxs-lookup"><span data-stu-id="54a74-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="54a74-103">Zkontrolujte, jestli je pro vaši organizaci zapnuté externí sdílení:</span><span class="sxs-lookup"><span data-stu-id="54a74-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="54a74-104">Přejděte na [stránku Doplňky &amp; služeb v Centru pro správu Microsoftu 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klikněte na **Weby**.</span><span class="sxs-lookup"><span data-stu-id="54a74-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="54a74-105">Zkontrolujte, zda je nastavení zapnuto.</span><span class="sxs-lookup"><span data-stu-id="54a74-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="54a74-106">Pokud je vybraná možnost "Jenom stávající externí uživatelé", ujistěte se, že je externí uživatel uveden v Centru pro správu Microsoftu 365.</span><span class="sxs-lookup"><span data-stu-id="54a74-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="54a74-107">Ujistěte se, že je pro web zapnuté externí sdílení.</span><span class="sxs-lookup"><span data-stu-id="54a74-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="54a74-108">Pro klasickou kolekci webů:</span><span class="sxs-lookup"><span data-stu-id="54a74-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="54a74-109">V novém Centru pro správu SharePointu klikněte v levém podokně na **Weby**.</span><span class="sxs-lookup"><span data-stu-id="54a74-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="54a74-110">Vyberte web nebo weby a na pásu karet klikněte na **Sdílení**.</span><span class="sxs-lookup"><span data-stu-id="54a74-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="54a74-111">Pro týmový web, který patří do skupiny Office 365 nebo komunikačního webu:</span><span class="sxs-lookup"><span data-stu-id="54a74-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="54a74-112">Tyto nové typy webů mají stejné nastavení sdílení jako nastavení pro celou organizaci, pokud nastavení pro celou organizaci neumožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlášení.</span><span class="sxs-lookup"><span data-stu-id="54a74-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="54a74-113">V takovém případě umožňují weby sdílení s novými a stávajícími externími uživateli, kteří se přihlašují.</span><span class="sxs-lookup"><span data-stu-id="54a74-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="54a74-114">Pokud chcete změnit nastavení pro konkrétní weby, použijte nové Centrum pro správu SharePointu nebo PowerShell.</span><span class="sxs-lookup"><span data-stu-id="54a74-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="54a74-115">[Další informace](https://go.microsoft.com/fwlink/?linkid=871863)</span><span class="sxs-lookup"><span data-stu-id="54a74-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="54a74-116">Externí nastavení sdílení pro libovolný web může být více omezující než nastavení celé organizace, ale ne tolerantnější než nastavení pro celou organizaci.</span><span class="sxs-lookup"><span data-stu-id="54a74-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  


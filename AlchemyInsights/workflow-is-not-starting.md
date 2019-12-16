---
title: Pracovní postup se nespouští
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: cf7bd95e9a8f1d0842f0abcf82c758d649e80c0f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049330"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="fcdbf-102">Pracovní postup se nespouští</span><span class="sxs-lookup"><span data-stu-id="fcdbf-102">Workflow is not starting</span></span>

- <span data-ttu-id="fcdbf-103">Nelze spustit pracovní postupy služby SharePoint 2010 a SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="fcdbf-104">Pokud pracovní postup nelze spustit, může se jednat o dočasný problém se službou, kde mohou uživatelé zaznamenat občasná zpoždění v průběhu pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="fcdbf-105">Zkontrolujte [řídicí panel stavu služby](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) a zjistěte, zda je v organizaci ohrožena.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="fcdbf-106">Pokud od prvního vydání tohoto problému uplynulo více než 24 hodin, zadejte do protokolu lístek odborné pomoci.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="fcdbf-107">V mnoha případech už pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="fcdbf-108">K dokončení řešení nám prosím dejte alespoň 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="fcdbf-109">Pracovní postupy služby SharePoint 2010 jsou zpožděny při spuštění.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="fcdbf-110">K tomu dojde, pokud je pracovní postup spuštěn ve velkých dávkách.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="fcdbf-111">(například když je přidáno několik položek najednou).</span><span class="sxs-lookup"><span data-stu-id="fcdbf-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="fcdbf-112">Pracovní postupy nejsou navrženy pro běh v reálném čase, takže zpoždění je podle návrhu chování.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="fcdbf-113">Pokud je pracovní postup složitý (Extensible Object Markup Language) (XMOL), může být kompilace pomalá.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="fcdbf-114">Podívejte se na [Tento](https://support.microsoft.com//kb/3043697) článek.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="fcdbf-115">Tento pracovní postup byste měli zjednodušit nebo změnit jeho návrh pomocí typu platformy Microsoft SharePoint 2013 Workflow.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="fcdbf-116">Pokud se historie pracovního postupu zvětšila, budete pravděpodobně chtít vymazat položky nebo vytvořit nový seznam historie.</span><span class="sxs-lookup"><span data-stu-id="fcdbf-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="fcdbf-117">Další informace: [Vyčistit historii pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="fcdbf-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="fcdbf-118">Související témata</span><span class="sxs-lookup"><span data-stu-id="fcdbf-118">Related topics</span></span>
<span data-ttu-id="fcdbf-119">Chcete vyzkoušet program Microsoft Flow ve službě SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="fcdbf-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="fcdbf-120">Vytvořit tok</span><span class="sxs-lookup"><span data-stu-id="fcdbf-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="fcdbf-121">Služba SharePoint a tok</span><span class="sxs-lookup"><span data-stu-id="fcdbf-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 



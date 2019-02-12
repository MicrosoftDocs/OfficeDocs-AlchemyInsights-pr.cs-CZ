---
title: Chybějící pracovní postup se nepodařilo aktivovat.
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: ce088227a3206fa05b99331fdb022fbe4886203f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29917561"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="cb2c9-102">Chybějící pracovní postup se nepodařilo aktivovat.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="cb2c9-103">V kolekci webů Microsoft SharePoint nelze přidat do seznamu nebo knihovny globálně opakovaně použitelný pracovní postup (například "schválení – SharePoint 2010").</span><span class="sxs-lookup"><span data-stu-id="cb2c9-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="cb2c9-104">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="cb2c9-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="cb2c9-105">Otevřete kořenový web kolekce webů v aplikaci SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="cb2c9-106">Ve skupinovém rámečku **Objekty sítě**vyberte **pracovní postupy**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="cb2c9-107">V části **Nový** pás karet **pracovních postupů** vyberte **Opakovaně použitelného pracovního postupu**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="cb2c9-p101">Ve formuláři **Vytvořit opakovaně použitelného pracovního postupu** zadejte název \*\* *Repair2010* \*\*. Pro **Typ platformy** **Pracovního postupu služby SharePoint 2010**klepněte a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="cb2c9-110">V části **ukládání** **pracovního postupu** pásu karet vyberte možnost **Publikovat**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="cb2c9-p102">V části **Správa** **pracovního postupu** pásu karet vyberte **Publikování globálně**. V dialogovém okně potvrzení klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="cb2c9-p103">Ve webovém prohlížeči vyhledejte kořenový web kolekce webů a potom přístup k **Nastavení webu** \> **Funkce kolekce webů**. Potom přepnout funkce **pracovních postupů** :</span><span class="sxs-lookup"><span data-stu-id="cb2c9-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="cb2c9-115">· Je-li funkce *aktivní* , klepněte na tlačítko **dezaktivovat** a potom klepněte na tlačítko **Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="cb2c9-116">· Je-li funkce *deaktivovány* , klepněte na tlačítko **Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="cb2c9-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="cb2c9-117">Další informace naleznete v následujícím [článku](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="cb2c9-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  


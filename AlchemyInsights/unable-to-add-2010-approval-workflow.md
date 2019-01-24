---
title: Nelze přidat pracovní postup schválení 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: a83a9621ca0f7764d3f2c0a698dbffd80d55e80c
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29463391"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="cba3a-102">Nelze přidat pracovní postup schválení 2010</span><span class="sxs-lookup"><span data-stu-id="cba3a-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="cba3a-103">V kolekci webů Microsoft SharePoint nelze přidat do seznamu nebo knihovny globálně opakovaně použitelný pracovní postup (například "schválení – SharePoint 2010").</span><span class="sxs-lookup"><span data-stu-id="cba3a-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="cba3a-104">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="cba3a-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="cba3a-105">Otevřete kořenový web kolekce webů v aplikaci SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="cba3a-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="cba3a-106">Ve skupinovém rámečku **Objekty sítě**vyberte **pracovní postupy**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="cba3a-107">V části **Nový** pás karet **pracovních postupů** vyberte **Opakovaně použitelného pracovního postupu**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="cba3a-p101">Ve formuláři **Vytvořit opakovaně použitelného pracovního postupu** zadejte název \*\* *Repair2010* \*\*. Pro **Typ platformy** **Pracovního postupu služby SharePoint 2010**klepněte a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="cba3a-110">V části **ukládání** **pracovního postupu** pásu karet vyberte možnost **Publikovat**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="cba3a-p102">V části **Správa** **pracovního postupu** pásu karet vyberte **Publikování globálně**. V dialogovém okně potvrzení klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="cba3a-p103">Ve webovém prohlížeči vyhledejte kořenový web kolekce webů a potom přístup k **Nastavení webu** \> **Funkce kolekce webů**. Přepnout funkci **pracovní postupy** :</span><span class="sxs-lookup"><span data-stu-id="cba3a-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="cba3a-115">· Je-li funkce *aktivní* , klepněte na tlačítko **dezaktivovat** a potom klepněte na tlačítko **Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="cba3a-116">· Je-li funkce *deaktivovány* , klepněte na tlačítko **Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="cba3a-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="cba3a-117">Další informace naleznete v následujícím [článku](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="cba3a-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  


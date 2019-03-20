---
title: stejný jako název souboru je nejlepší
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: ec979c2f2246fa06945b79bbb9348a7a57ad5180
ms.sourcegitcommit: b3cf5130ac8118f0fed66abe5286aa80ee91af52
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/19/2019
ms.locfileid: "30683842"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="e626d-102">Nejsou k dispozici požadované Alchymie hlavičku H1, H2 je.</span><span class="sxs-lookup"><span data-stu-id="e626d-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="e626d-103">Doporučené postupy a pokyny pro vytváření Alchymie:</span><span class="sxs-lookup"><span data-stu-id="e626d-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="e626d-104">**Nelze vnořit Alchymie poznatky ve složkách**- tím dojde k porušení struktury adres url.</span><span class="sxs-lookup"><span data-stu-id="e626d-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="e626d-105">Díváme se do tohoto řešení.</span><span class="sxs-lookup"><span data-stu-id="e626d-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="e626d-106">Malá písmena názvy souborů s pomlčkami ex prostory by měly mít soubory ve složce **AlchemyInsights** .</span><span class="sxs-lookup"><span data-stu-id="e626d-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="e626d-107">***how-k-povolit-soudní pře podržet***.</span><span class="sxs-lookup"><span data-stu-id="e626d-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="e626d-108">Zahrňte ID ID pravidla nebo plechovka z [Alchymie partnerský portál](https://alchemyportal.azurewebsites.net) ms.custom pole.</span><span class="sxs-lookup"><span data-stu-id="e626d-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="e626d-109">ex.</span><span class="sxs-lookup"><span data-stu-id="e626d-109">ex.</span></span> <span data-ttu-id="e626d-110">***MS.Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="e626d-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="e626d-111">V horní části tohoto souboru jako šablony použijte zbývající metadata.</span><span class="sxs-lookup"><span data-stu-id="e626d-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="e626d-112">Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight.</span><span class="sxs-lookup"><span data-stu-id="e626d-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="e626d-113">Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby.</span><span class="sxs-lookup"><span data-stu-id="e626d-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="e626d-114">H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.</span><span class="sxs-lookup"><span data-stu-id="e626d-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="e626d-115">Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně</span><span class="sxs-lookup"><span data-stu-id="e626d-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="e626d-116">Seznamy s odrážkami jsou jemné</span><span class="sxs-lookup"><span data-stu-id="e626d-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="e626d-117">Číslované seznamy příliš</span><span class="sxs-lookup"><span data-stu-id="e626d-117">Numbered lists too</span></span>
    1. <span data-ttu-id="e626d-118">**Tučné písmo** a *kurzívu* jsou a-ok</span><span class="sxs-lookup"><span data-stu-id="e626d-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="e626d-119">Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.</span><span class="sxs-lookup"><span data-stu-id="e626d-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="e626d-120">Obrázky nejsou v tuto chvíli oficiálně podporována, ale je na cestovní mapy.</span><span class="sxs-lookup"><span data-stu-id="e626d-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="e626d-121">A to je ve skutečnosti již trochu příliš dlouhý.</span><span class="sxs-lookup"><span data-stu-id="e626d-121">And this is really already a bit too long.</span></span> <span data-ttu-id="e626d-122">Nejlepší je asi 400 znaků---</span><span class="sxs-lookup"><span data-stu-id="e626d-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="e626d-123">Jakmile váš obsah je připraven, živé větve ho vytáhněte.</span><span class="sxs-lookup"><span data-stu-id="e626d-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="e626d-124">Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url.</span><span class="sxs-lookup"><span data-stu-id="e626d-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="e626d-125">M</span><span class="sxs-lookup"><span data-stu-id="e626d-125">M</span></span>
---
title: Omezení služby SharePoint Online do klasického režimu
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: 76f0b5ed67d3220559d25dfd72c7535181a4513b
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34761752"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="b591d-102">Omezení služby SharePoint Online do klasického režimu</span><span class="sxs-lookup"><span data-stu-id="b591d-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="b591d-103">Některé organizace vyžadují stále klasický režim zkušenosti.</span><span class="sxs-lookup"><span data-stu-id="b591d-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="b591d-104">Když nejsou žádné plány k odebrání klasického režimu na nejnižší úrovni, je již možné omezit celou organizaci (nájemce) do klasického režimu pro seznamy a knihovny.</span><span class="sxs-lookup"><span data-stu-id="b591d-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="b591d-105">Správce bude mít následující možnosti spravovat jednotlivé seznamy a knihovny v klasickém režimu granulovaných přepínače opt-out, které poskytujeme na následujících úrovních:</span><span class="sxs-lookup"><span data-stu-id="b591d-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="b591d-106">kolekce webů</span><span class="sxs-lookup"><span data-stu-id="b591d-106">site collection</span></span>
- <span data-ttu-id="b591d-107">webu</span><span class="sxs-lookup"><span data-stu-id="b591d-107">site</span></span>
- <span data-ttu-id="b591d-108">seznam</span><span class="sxs-lookup"><span data-stu-id="b591d-108">list</span></span>
- <span data-ttu-id="b591d-109">Knihovna</span><span class="sxs-lookup"><span data-stu-id="b591d-109">library</span></span>

<span data-ttu-id="b591d-110">Dále se seznamy, které používají určité funkce a vlastní nastavení, které nejsou podporovány moderní se stále automaticky přepne do klasického režimu.</span><span class="sxs-lookup"><span data-stu-id="b591d-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="b591d-111">Od 1. dubna 2019, zakázat na úrovni klienta proces odhlášení moderní seznamu a knihovny bude spustit a pokračovat do 31. května 2019.</span><span class="sxs-lookup"><span data-stu-id="b591d-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="b591d-112">Seznamy a knihovny, které jsou v klasickém režimu v důsledku odhlášení klienta budou automaticky posunuty na moderní.</span><span class="sxs-lookup"><span data-stu-id="b591d-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="b591d-113">Pokud vyžadujete klasický režim naleznete v tématu Další informace [zde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) a PnP Powershell instrukce [zde](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) popisující možnosti a nástroje, které dnes na klasický režim rozhraní.</span><span class="sxs-lookup"><span data-stu-id="b591d-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>

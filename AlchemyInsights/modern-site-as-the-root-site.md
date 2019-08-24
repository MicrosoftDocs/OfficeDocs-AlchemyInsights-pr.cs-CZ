---
title: Moderní web jako kořenový Web.
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: d5ea73c967013822854dbd408d4628d991c90378
ms.sourcegitcommit: cd79ecca88b2cb166f78f44ab8bc4e8136729418
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/23/2019
ms.locfileid: "36620752"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="ee5bc-102">Moderní web jako kořenový web</span><span class="sxs-lookup"><span data-stu-id="ee5bc-102">Modern site as root site</span></span>

<span data-ttu-id="ee5bc-103">Jsme začaly zavedení nové funkce, která vám umožní vyměnit klasické webu kořenového webu s moderním webem.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-103">We have begun to rollout a new feature that will allow you to swap your classic site root site with a modern site.</span></span> <span data-ttu-id="ee5bc-104">Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="ee5bc-104">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="ee5bc-105">K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

>[!Important]
> <span data-ttu-id="ee5bc-106">Neodstraňujte klasické kořenového webu vytvoření moderní komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="ee5bc-107">To není podporován společností Microsoft.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="ee5bc-108">Odstranění kořenového webu bude všechny weby služby SharePoint v organizaci přístupný všem uživatelům, dokud obnovit web nebo vytvořit nový web na adrese URL stejné.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="ee5bc-109">Jsme budete komunikovat tuto funkci prostřednictvím Centra zpráv.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="ee5bc-110">Lze očekávat, že je funkce zapnuta v vašeho klienta krátce.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="ee5bc-111">Známé problémy týkající se výměny serverů</span><span class="sxs-lookup"><span data-stu-id="ee5bc-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="ee5bc-112">Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="ee5bc-113">Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="ee5bc-114">Neexistuje žádná ruční krok vyžaduje zde, to bude provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="ee5bc-115">Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="ee5bc-116">Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny.</span><span class="sxs-lookup"><span data-stu-id="ee5bc-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 

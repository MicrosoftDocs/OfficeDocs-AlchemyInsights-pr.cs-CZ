---
title: Zaměnit s moderním webu kořenového webu Classic
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: 0f6f962314d9099bd21c281a23ad2e95742da4a8
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270737"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="f958d-102">Zaměnit s moderním webu kořenového webu Classic</span><span class="sxs-lookup"><span data-stu-id="f958d-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="f958d-103">Pokud vaše prostředí byla nastavena před duben 2019, moderní web můžete změnit kořenový web pomocí Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="f958d-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="f958d-104">Pokud máte jiný server, který chcete použít jako kořenový web, můžete nahradit (swap) kořenovém webu ji.</span><span class="sxs-lookup"><span data-stu-id="f958d-104">If you have a different site that you want to use as your root site, you can replace (swap) the root site with it.</span></span> 
    - <span data-ttu-id="f958d-105">Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="f958d-105">Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="f958d-106">K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="f958d-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="f958d-107">Další funkce budou zavedeny brzy, bude možné nadále používat obsah na webu, ale převést stávající web do komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="f958d-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="f958d-108">Tyto možnosti budou vrácena postupně.</span><span class="sxs-lookup"><span data-stu-id="f958d-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="f958d-109">Dále zkontrolujte Centrum Office 365 zprávy aktualizace.</span><span class="sxs-lookup"><span data-stu-id="f958d-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="f958d-110">Známé problémy týkající se výměny serverů</span><span class="sxs-lookup"><span data-stu-id="f958d-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="f958d-111">Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="f958d-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="f958d-112">Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="f958d-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="f958d-113">Neexistuje žádná ruční požadovaným krokem – to bude provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="f958d-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="f958d-114">Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.</span><span class="sxs-lookup"><span data-stu-id="f958d-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="f958d-115">Pokud je zdrojový web serveru novinky týkající se organizace, aktualizujte adresu URL.</span><span class="sxs-lookup"><span data-stu-id="f958d-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="f958d-116">Zobrazit seznam všech organizačních diskusní servery.</span><span class="sxs-lookup"><span data-stu-id="f958d-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="f958d-117">Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny.</span><span class="sxs-lookup"><span data-stu-id="f958d-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>






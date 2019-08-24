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
# <a name="modern-site-as-root-site"></a>Moderní web jako kořenový web

Jsme začaly zavedení nové funkce, která vám umožní vyměnit klasické webu kořenového webu s moderním webem. Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) . K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě. 

>[!Important]
> Neodstraňujte klasické kořenového webu vytvoření moderní komunikační sítě. To není podporován společností Microsoft. Odstranění kořenového webu bude všechny weby služby SharePoint v organizaci přístupný všem uživatelům, dokud obnovit web nebo vytvořit nový web na adrese URL stejné. Jsme budete komunikovat tuto funkci prostřednictvím Centra zpráv. Lze očekávat, že je funkce zapnuta v vašeho klienta krátce.

## <a name="known-issues-with-swapping-sites"></a>Známé problémy týkající se výměny serverů
- Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.
- Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání. Neexistuje žádná ruční krok vyžaduje zde, to bude provedeno automaticky.
- Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.
- Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny. 

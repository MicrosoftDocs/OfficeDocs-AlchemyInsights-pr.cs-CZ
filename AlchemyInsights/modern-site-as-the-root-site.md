---
title: Moderní web jako kořenový Web.
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1874"
- "9000265"
ms.openlocfilehash: b30fc3258bb76c0ab4bf10af0ec9317417f7c663
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232708"
---
# <a name="modern-site-as-root-site"></a>Moderní web jako kořenový web

Jsme začaly zavedení nové funkce, která vám umožní vyměnit klasické webu kořenového webu s moderním webem. Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) . K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě. 

>[!Important]
> Neodstraňujte klasické kořenového webu vytvoření moderní komunikační sítě. To není podporován společností Microsoft. Odstranění kořenového webu bude všechny weby služby SharePoint v organizaci přístupný všem uživatelům, dokud obnovit web nebo vytvořit nový web na adrese URL stejné. Jsme budete komunikovat tuto funkci prostřednictvím Centra zpráv. Lze očekávat, že je funkce zapnuta v vašeho klienta krátce.

## <a name="known-issues-with-swapping-sites"></a>Známé problémy týkající se výměny serverů
- Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.
- Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání. Neexistuje žádná ruční krok vyžaduje zde, to bude provedeno automaticky.
- Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.
- Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny. 

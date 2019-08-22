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
ms.openlocfilehash: ffb1466fe436d6cab7ae5fdd60c671f5dd2654dd
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36501072"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Zaměnit s moderním webu kořenového webu Classic

Pokud vaše prostředí byla nastavena před duben 2019, moderní web můžete změnit kořenový web pomocí Microsoft PowerShell:

- Pokud máte jiný server, který chcete použít jako kořenový web, můžete nahradit (swap) kořenovém webu ji. 
    - Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) . K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě. 

- Další funkce budou zavedeny brzy, bude možné nadále používat obsah na webu, ale převést stávající web do komunikační sítě. 
>[!Important]
>Tyto možnosti budou vrácena postupně. Dále zkontrolujte Centrum Office 365 zprávy aktualizace. 

## <a name="known-issues-with-swapping-sites"></a>Známé problémy týkající se výměny serverů

- Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.
- Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání. Neexistuje žádná ruční požadovaným krokem – to bude provedeno automaticky.
- Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.
- Pokud je zdrojový web serveru novinky týkající se organizace, aktualizujte adresu URL.Zobrazit seznam všech organizačních diskusní servery.
- Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny.






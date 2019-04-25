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
ms.openlocfilehash: 37398436435fb72cb5c8dca2d0798b86a0c8ccc9
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32366324"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Nejsou k dispozici požadované Alchymie hlavičku H1, H2 je.
Doporučené postupy a pokyny pro vytváření Alchymie:

1. **Nelze vnořit Alchymie poznatky ve složkách**- tím dojde k porušení struktury adres url. Díváme se do tohoto řešení.
1. Malá písmena názvy souborů s pomlčkami ex prostory by měly mít soubory ve složce **AlchemyInsights** . ***how-k-povolit-soudní pře podržet***.
    1. Zahrňte ID ID pravidla nebo plechovka z [Alchymie partnerský portál](https://alchemyportal.azurewebsites.net) ms.custom pole. ex. ***MS.Custom: 100021***
1. V horní části tohoto souboru jako šablony použijte zbývající metadata.
1. Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight. 
    > [!NOTE]
    > Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby. H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.
1. Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně
    1. Seznamy s odrážkami jsou jemné
    1. Číslované seznamy příliš
    1. **Tučné písmo** a *kurzívu* jsou a-ok
    1. Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.
    1. Obrázky nejsou v tuto chvíli oficiálně podporována, ale je na cestovní mapy.

A to je ve skutečnosti již trochu příliš dlouhý. Nejlepší je asi 400 znaků---

Jakmile váš obsah je připraven, živé větve ho vytáhněte. Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url. M
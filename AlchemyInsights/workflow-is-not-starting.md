---
title: Pracovní postup se nespouští
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 2d85dcf9111d48cb529c583c733823b404eb3188
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36738082"
---
# <a name="workflow-is-not-starting"></a>Pracovní postup se nespouští

- Nelze spustit pracovní postupy služby SharePoint 2010 a SharePoint 2013.

    - Pokud pracovní postup nelze spustit, může se jednat o dočasný problém se službou, kde mohou uživatelé zaznamenat občasná zpoždění v průběhu pracovního postupu. Zkontrolujte [řídicí panel stavu služby](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) a zjistěte, zda je v organizaci ohrožena.

    - Pokud od prvního vydání tohoto problému uplynulo více než 24 hodin, zadejte do protokolu lístek odborné pomoci. V mnoha případech už pracujeme na řešení. K dokončení řešení nám prosím dejte alespoň 24 hodin.

- Pracovní postupy služby SharePoint 2010 jsou zpožděny při spuštění.

    - K tomu dojde, pokud je pracovní postup spuštěn ve velkých dávkách. (například když je přidáno několik položek najednou).

    - Pracovní postupy nejsou navrženy pro běh v reálném čase, takže zpoždění je podle návrhu chování.

   -  Pokud je pracovní postup složitý (Extensible Object Markup Language) (XMOL), může být kompilace pomalá. Podívejte se na [Tento](https://support.microsoft.com//kb/3043697) článek.

    - Tento pracovní postup byste měli zjednodušit nebo změnit jeho návrh pomocí typu platformy Microsoft SharePoint 2013 Workflow.

    - Pokud se historie pracovního postupu zvětšila, budete pravděpodobně chtít vymazat položky nebo vytvořit nový seznam historie.

        Další informace: [Vyčistit historii pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)


## <a name="related-topics"></a>Související témata
Chcete vyzkoušet program Microsoft Flow ve službě SharePoint Online?
- [Vytvořit tok](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Služba SharePoint a tok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 



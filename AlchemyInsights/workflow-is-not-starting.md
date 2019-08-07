---
title: Pracovní postup nelze spustit.
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
ms.openlocfilehash: efd17c302ae6d857207e87e94d74d3794e94a83a
ms.sourcegitcommit: 204be4a6ae03700b75eae6b09b4e9ab283089fbf
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/03/2019
ms.locfileid: "36171769"
---
# <a name="workflow-is-not-starting"></a>Pracovní postup nelze spustit.

- Pracovní postupy služby SharePoint 2010 a SharePoint 2013 nejsou počáteční.

    Pokud váš pracovní postup nelze spustit, pravděpodobně problém s dočasnou službu kde uživatelů může docházet k občasným zpožděním s průběh pracovního postupu. Kontrola [Řídicí panel stavu služeb](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) zobrazíte, pokud vaše organizace klesá.

    Pokud více než 24 hodin uplynulo od poprvé viděli tento problém, zkontrolujte protokolu lístek podpory. V mnoha případech již pracujeme na řešení. Uveďte, prosím, nás alespoň 24 hodin, řešení.

- Pracovní postupy služby SharePoint 2010 odloženo na start.

    K tomu dochází, pokud je aktivován pracovní postup ve velkých dávkách. (například když některé položky jsou přidány najednou).

    Pracovní postupy nejsou určeny ke spuštění v reálném čase, takže zpoždění je chování podle návrhu.

    Pokud pracovní postup je složité Extensible objekt Markup Language (XMOL), může být pomalé kompilace. Zkontrolujte, zda [v tomto](https://support.microsoft.com/en-us/kb/3043697) článku.

    By měla zjednodušit pracovního postupu nebo změnit návrh pomocí typ platformy Microsoft SharePoint 2013 pracovního postupu.

    Také rozrostla historie pracovního postupu, můžete chtít vymazat položky nebo vytvořit nový seznam historie.

    Další informace: [Odstranění historie pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)


## <a name="related-topics"></a>Související témata
Chcete zkusit aplikaci Microsoft toku v Online služby SharePoint?
- [Vytvoření toku](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint a toku](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


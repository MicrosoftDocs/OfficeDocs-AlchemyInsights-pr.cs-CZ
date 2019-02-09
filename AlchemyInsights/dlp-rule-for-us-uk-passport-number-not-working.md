---
title: DLP pravidlo pro US / UK číslo pasu nefunguje
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: ec7f11676982b56a46c83bf276c2212ce765ba6f
ms.sourcegitcommit: ca06ef831226d629de3057a0df85e017b80f3356
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/08/2019
ms.locfileid: "29786691"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problémy s DLP - USA / UK čísla účtu služby Passport

Máte problémy s **Dat ztráta prevence (DLP)** obsahující obsahu nefunguje **US / UK číslo pasu** při použití typu DLP citlivých informací v O365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro co zásady DLP hledá Pokud je vyhodnocena. 
  
Například **US / UK číslo pasu** zásad nakonfigurován s konfidenční úrovni 75 %, následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit 
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Číslice devět 
    
- **[Vzorek:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devět po sobě jdoucích číslic. 
    
- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, neexistuje žádný kontrolní součet 
    
- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Zásady DLP je 75 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků: 
    
  - Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.
    
  - Klíčové slovo z Keyword_passport nebyla nalezena.
    
    Například následující ukázka by znamenala pro **US / UK číslo pasu** zásad: Passport USA číslo 123456789 
    
Další informace o co je požadováno pro americké / číslo pasu UK zjistit obsah, naleznete v následující části v tomto článku: [co citlivé informace typy vzhledu pro USA / UK číslo pasu](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  


---
title: Nesynchronizace služby Active Directory
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001688"
- "3754"
ms.openlocfilehash: 3abad160ab28922685d235a1fa546105e31757fb
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265154"
---
# <a name="active-directory-not-syncing"></a>Nesynchronizace služby Active Directory

Pokud přijímáte chyby synchronizace, například "žádná nedávná synchronizace", nebo si všimnete stavu synchronizace adresářů na portálu pro správu Office, říká: "Poslední synchronizace před více než 3 dny", může se to být, že AADConnect má nesprávné nastavení nebo nedostatečné oprávnění k provedení synchronizace.  

Přeinstalace AADConnect pomocí expresního nastavení může problém rychle vyřešit:

1. [Stáhněte si nejnovější verzi aadconnectu](https://go.microsoft.com/fwlink/?LinkId=615771).

2. [Postupujte podle pokynů pro expresní instalaci](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).

Další informace o účtech služby AADConnect najdete v tématu [Azure AD Connect: Účty a oprávnění](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).

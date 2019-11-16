---
title: Odstraňování problémů s problémem-uživatel nenalezen v adresáři
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 59713231da25be441e7c05d788337e66bf17265a
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768794"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Odstraňování problémů s problémem-uživatel nenalezen v adresáři

Pokud se uživatelům zobrazuje chybová zpráva "uživatel nebyl nalezen" v adresáři, opakujte akci, pokud je typ problému uživatel není v adresáři.

K vyřešení problému lze provést následující kroky.

- Ujistěte se, že účet, který přijal e-mailovou pozvánku, je stejný účet, který se používá k pozdějšímu přihlášení. Ujistěte se, že uživatel používá stejný účet k přijmutí pozvání a přihlášení na web. 

Další informace naleznete v tématu [Správa aliasů pro účet</a> společnosti Microsoft za účelem správy sady Office 365 Login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases). 

- Přejděte na každý web (y), ve kterém uživatel chybu obdržel. 

Přidejte "/_layouts/15/People.aspx/MembershipGroupId = 0" (v rámci uvozovek) na konec adresy URL webu. 

Příklad: https://< "contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.

- Vyberte uživatele ze seznamu.

- Klepněte na tlačítko **Odebrat oprávnění uživatele** z pásu karet. 
-  Přidejte uživatele zpět a znovu odešlete pozvání uživateli.


---
title: Nelze odstranit položky na SharePointu nebo OneDrivu.
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: fd12115214cc28b822cf7fa57fe9b86f76f7beb1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806104"
---
# <a name="unable-to-delete-items"></a>Nelze odstranit položky

Zásady uchovávání informací mohou způsobit, že je nutné zakázat nebo vyloučit odpovídající blokování, které je příčinou tohoto problému. Po odebrání zásad uchovávání informací nebo držení může trvat až 24 hodin, než se změna projeví. Ujistěte se, že u položky neexistuje nastavení [zásad uchovávání informací](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) .

Web mohl mít překročen limit úložiště, zvýšit [kvótu webu](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) a odstranit položku.

Ujistěte se, že položka není [rezervována](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) pro jiného uživatele.

Správci můžou použít [vzory a postupy SharePointu](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) , které obsahují knihovnu příkazů PowerShellu, které umožňují provádět složité akce správy, jako je například vynutit odstranění stubborn položek.
- [Odebrání souboru PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Odebrání složky PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Odebrání položky seznamu PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Odebrat seznam PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Odebrání pole PNP (sloupec)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
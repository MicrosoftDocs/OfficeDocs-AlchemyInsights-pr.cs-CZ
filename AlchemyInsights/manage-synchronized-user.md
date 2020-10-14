---
title: Správa synchronizovaných uživatelů
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 7bf7d3f00308ff6bc973cd52e09ca51c5fd0f45b
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/13/2020
ms.locfileid: "48451393"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Nelze nastavit primární e-mailovou adresu, změnit atributy uživatele nebo odebrat či odstranit synchronizovaného uživatele.

Pokud je synchronizace adresářů pro vaše prostředí povolená, některé atributy uživatelů nebo objektů se nedají změnit pomocí centra pro správu Microsoft 365.

Chcete-li spravovat synchronizované uživatele a všechny jejich atributy, použijte konzolu pro správu Uživatelé a skupiny služby Active Directory (adsiedit. msc).  

Můžete taky změnit jednotlivé uživatele nebo atributy pro synchronizované uživatele pomocí PowerShellu, jako je to vidět v těchto běžných příkladech:

`Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

`Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

`Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`

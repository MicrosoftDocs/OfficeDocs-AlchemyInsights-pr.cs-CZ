---
title: Nezobrazující se ikona kalendáře v klientovi Teams
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001219"
- "4375"
ms.openlocfilehash: 6a3f02b69d160c7dce68ed03df59c0d7d1f32f0f
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819946"
---
# <a name="calendar-icon-not-showing-in-teams-client"></a>Nezobrazující se ikona kalendáře v klientovi Teams

Karta kalendáře v Teams vyžaduje přístup k poštovní schránce Exchange prostřednictvím webových služeb Exchange. Poštovní schránka Exchange může být online nebo místní. V případě online uživatelů, kteří nevidí kartu Kalendář, zkontrolujte, jestli [mají licenci pro poštovní schránku Exchange Online a že poštovní schránka je povolena](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).

Pokud má uživatel v Exchange Online platnou poštovní schránku, ale karta Kalendář se pořád nezobrazuje, je možné, že dochází k potížím se sítí. U ovlivněných uživatelů použijte nástroj [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) a spusťte **testy připojení Webových služeb systému Microsoft Exchange**.

Nakonec zaškrtnutím políčka [Aplikace Teams – zásady nastavení aplikací](https://admin.teams.microsoft.com/policies/app-setup) zajistíte, že se aplikace Kalendář neodebere ze zásad použitých u uživatele (nejpravděpodobněji **Globální (výchozí nastavení celé organizace)**.

Pokud jsou vaši uživatelé místní, budete muset ověřit, jestli je hybridní konfigurace v pořádku. K řešení potíží použijte [průvodce hybridní konfigurací](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent).

Poznámka: [Teams vyžaduje Exchange 2016 CU3 nebo novější](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).

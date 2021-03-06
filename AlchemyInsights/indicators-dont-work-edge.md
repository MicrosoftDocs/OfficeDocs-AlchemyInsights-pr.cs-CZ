---
title: Indikátory nefungují v prohlížeči Edge
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 05/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11230"
- "9005470"
ms.openlocfilehash: df62d965e0dc2ddb656571af99b1e4c3cb52ea35
ms.sourcegitcommit: 4b504650e11adb9894c37b6d8608b53f9d5fc13d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/25/2021
ms.locfileid: "52676131"
---
# <a name="indicators-dont-work-using-edge-browser"></a>Indikátory nefungují v prohlížeči Edge

Po vytvoření indikátoru ho Edge (Smartscreen) nebude ctít. Další informace najdete v tématu Vytvoření indikátorů pro IP adresy a [adresy URL/domény](/microsoft-365/security/defender-endpoint/indicator-ip-domain).

## <a name="step-1-ensure-the-following"></a>Krok 1: Zkontrolujte následující:

- Ověřte, jestli je indikátor správný (žádné překlepy v IP/URL, správná akce, správné skupiny RBAC).
- Počkejte minimálně 2 hodiny po vytvoření indikátoru, aby se zohlednila jakákoli možná latence.
- Ujistěte se, že jsou systém(y) v programu Microsoft Defender for Endpoint.
- Ověřte, jestli systém(y) může komunikovat s cloudem.
- Ověřte, jestli je smartscreen povolený a dostupný, a to tak, že se dostanete na [testovací web.](https://demo.smartscreen.msft.net)

## <a name="step-2-troubleshoot-the-potential-issue"></a>Krok 2: Řešení potenciálního problému

- Ujistěte se, že klient splňuje požadavky. Podrobnosti najdete v tématu Vytvoření indikátorů pro IP adresy a [adresy URL/domény](/microsoft-365/security/defender-endpoint/indicator-ip-domain).
- Ujistěte se, že používáte nejnovější verzi prohlížeče Edge. Informace o nejnovější verzi najdete v tématu Zjistěte, kterou [Microsoft Edge máte](https://support.microsoft.com/microsoft-edge/find-out-which-version-of-microsoft-edge-you-have-c726bee8-c42e-e472-e954-4cf5123497eb).
- Restartujte prohlížeč Edge.
- Přejděte na web, pro který máte nastavit indikátor. Pokud se web nezobrazuje očekávaným způsobem, pokračujte krokem 3. 

## <a name="step-3-collect-data"></a>Krok 3: Shromažďování dat

- Shromažďování **diagnostických dat MDEClientAnalyzer** Pokyny najdete v tématu Problémy s zařízeními pro připojení k [Microsoft Defenderu pro koncový bod](issues-with-onboarding-machines.md).
- Pokud máte s instalací a shromažďováním stop fiddlerů problémy, podívejte se na [stránku Telerik Fiddler](http://www.telerik.com/fiddler).
- Pokud upřednostňujete pokyny od podpory Microsoftu, vyberte níže ikonu Podpora a otevřete tak případ podpory.

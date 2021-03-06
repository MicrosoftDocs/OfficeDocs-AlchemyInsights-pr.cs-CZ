---
title: 2491 Upozornění na e-mailové zprávy z zásady Phish Delivered due to tenant or user override
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2b373423cf3e63b76a62465dd62076c023580e94
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/19/2021
ms.locfileid: "52544571"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Upozornění na e-mailové zprávy z zásady Phish Delivered (Doručeno z důvodu přepsání tenanta nebo uživatele)

Pro tenanty s licencí Microsoft Defender pro Office 365 P1 a P2 byla vydaná výchozí zásada upozornění s názvem Phish Delivered z důvodu přepsání tenanta nebo uživatele. Pokud jste dostali toto upozornění, tady je postup, jak prozkoumat:

1. V upozornění klikněte na **Zobrazit** upozornění a přejděte na stránku **Upozornění** v Centru & dodržování předpisů.

2. Výběrem upozornění zobrazíte možnost Zobrazit **seznam zpráv** nebo Zobrazit zprávy **v Průzkumníkovi.** Obě tyto možnosti vás převezou k podrobnostem zprávy, která obsahuje ID zprávy. Všimněte si, že odkaz Průzkumníka hrozeb automaticky vyfiltruje zprávy, které splňují kritéria upozornění. Možná budete muset upravit filtr data v Průzkumníkovi hrozeb.

Zpráva útoku phishing byla doručena z důvodu ručně nakonfigurovaného přepsání:

- Povolený odesílatel nebo doména nastavená uživatelem

- Povolený odesílatel nebo doména nastavená správcem v zásadách ochrany proti spamu

- Povolená IP adresa v zásadách filtru připojení

- Pravidlo toku pošty (označované taky jako pravidlo přenosu), které je nakonfigurované tak, aby povoloval zprávy.

Pokud se domníváte, že zpráva byla nesprávně označená jako phish, použijte doplněk Outlook [Report Message](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) (Zpráva sestavy) k odeslání ukázek zpráv do Microsoftu.

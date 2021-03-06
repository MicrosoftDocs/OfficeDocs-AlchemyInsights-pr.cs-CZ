---
title: Problémy s přihlášením k aplikacím Microsoft 365
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: c64cf2c9dbf63caad22e54ae801adc3ed8ff0f62
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/15/2021
ms.locfileid: "51832996"
---
# <a name="fixing-the-microsoft-365-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a>Oprava zpráv o tom, že modul Důvěryhodné platformy vašeho počítače nefunguje správně, opravte aplikace Microsoft 365.

Pokud chcete tuto chybu vyřešit, vyzkoušejte následující:

- Nainstalujte si nejnovější aktualizace [pro Windows a](https://support.microsoft.com/help/4027667/windows-10-update) [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- [Vymažte přihlašovací údaje Office](https://docs.microsoft.com/office/troubleshoot/office-suite-issues/another-account-already-signed-in#step-4-clear-cached-credentials-on-the-computer) pomocí Správce přihlašovacích údajů systému Windows.<br/>
    **Poznámka:** Cesty registru pro Office 2016 se změnily na 16.0. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Zkuste [proces obnovení uživatele a](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) opravte chyby modulu ČIPM (Trusted Platform Module).
- Pomocí následujících kroků nastavte EnableADAL = 0:  
    1. Klikněte pravým tlačítkem myši na tlačítko Start systému Windows, zvolte **Spustit,** zadejte **regedit** a pak zvolte **OK.**
    2. Výběrem **možnosti Ano** povolíte Editoru registru provádět změny ve vašem zařízení.
    3. V Editoru registru přidejte hodnotu DWORD **EnableADAL** s nastavením **0** v části HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.

Další informace najdete v článku Problémy s připojením při přihlašování po aktualizaci na [build 16.0.7967 Office 2016 ve Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).
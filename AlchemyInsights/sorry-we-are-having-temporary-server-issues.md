---
title: Oprava aplikací sady Office Omlouváme se, došlo k dočasné chybě serveru.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627983"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a>Oprava aplikací sady Office "Promiňte, dochází k dočasným potížím se serverem"

Zobrazí-li se tato zpráva, postupujte takto:

1. Zkontrolujte bránu firewall, antivirový software a nastavení serveru proxy, abyste potvrdili, že neblokují internetový přístup k aplikacím sady Office. Viz [adresy URL sady Office 365 a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Přejděte ke **** > spuštění**a zadejte**příkaz **Services. msc**. Zkontrolujte, zda jsou spuštěny následující služby:
    - Automatické nastavení zařízení připojených k síti
    - Služba Network list Service
    - Povědomí o síťovém umístění
    - Protokol událostí systému Windows

Není-li některá z těchto služeb spuštěna, pokuste se jej spustit. Pokud při spouštění služby dojde k potížím, spusťte pomocí příkazového řádku se zvýšenými oprávněními následující příkaz:

**sfc/scannow**

Po dokončení tohoto příkazu restartujte počítač.

Podrobné informace naleznete v tématu ["Lituji, ale nemůžeme se připojit k vašemu účtu. Při aktivaci sady Office ze sady Office 365 opakujte akci později](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).
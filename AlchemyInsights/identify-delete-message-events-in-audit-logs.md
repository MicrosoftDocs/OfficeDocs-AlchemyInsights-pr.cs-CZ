---
title: Identifikovat odstranit zprávy události v protokolech auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 0fb5d6aa0c99f7f68459c40302869bed69583b3f
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34755146"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Protokoly auditu pro odstraněné e-mailové zprávy

Spuštění v lednu 2019, Microsoft je zapnutí ve výchozím nastavení je protokolování auditování poštovní schránky. Jinak můžete ověřit události odstranit zprávy pro určitého uživatele, je třeba ručně povolit auditování akce odstranění. Pokud auditování poštovní schránky ve vaší organizaci nebo pro konkrétního uživatele je již povoleno protokolování, postupujte následujícím způsobem.

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)

2. Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** . Zadejte uživatelské jméno uživatele, který chcete prozkoumat (uživatel, který odstraněné položky). V oblasti **aktivity** vyberte **odstraněné zprávy ze složky Odstraněná pošta** a **Moved zprávy do složky Odstraněná pošta**.

4. Klepněte na tlačítko **Hledat**.

V seznamu výsledků vyberte záznam auditu. V plovoucí panel Podrobnosti klepněte na tlačítko **Další informace**. Další informace o odstraněné položky (například předmět a umístění položky po odstranění) se zobrazí v poli **AffectedItems** . Vlastnost **ClientInfoString** se zobrazí, pokud došlo k odstranění v aplikaci Outlook, aplikace Outlook na webu (dříve známá jako aplikace Outlook Web App) nebo jiné zařízení.

Další informace naleznete v tématu [určení, která nastavila e-mail dál pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Poznámka**: Nelze načíst odstraněné položky pomocí funkce protokolu auditu. Chcete-li obnovit odstraněné zprávy v aplikaci Outlook na webu, naleznete v tématu [Obnovit odstraněné položky v aplikaci Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).

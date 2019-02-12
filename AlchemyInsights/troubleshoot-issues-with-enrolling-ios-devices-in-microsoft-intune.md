---
title: Řešení problémů s zápis zařízení iOS v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: d28dca4fccf823e627dd179f828ba3b8baf843a6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29924761"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Řešení problémů s zápis zařízení iOS v Microsoft Intune

Zobrazit zdroje uvedené níže nyní vyřešit váš problém. 
  
Některé běžné chybové zprávy a postup řešení:
  
- **Zařízení Cap dosaženo** Uživatel má více zařízení, než je limit zařízení zapsán. Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Této služby není podporován. Žádné zásady zápisu:** názvy Apple Push oznámení služby (APN) je nutné nakonfigurovat nebo obnoven. Přečtěte [dokument](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) pro pokyny, jak na to. 
    
- **Neplatný typ licence uživatele nebo uživatelské jméno není rozpoznán:** Uživatel musí být přiřazen licenci pro Intune a EMS. Zkontrolujte přiřazení licence prostřednictvím tyto dokumenty: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo [portálu Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).
    
Další zdroje pomoci vyřešit váš problém:
  
1. Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu. Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti. 
    
2. Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Zjistěte, jak zapsat zařízení iOS v Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).
    


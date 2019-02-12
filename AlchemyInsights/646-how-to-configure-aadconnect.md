---
title: 646 jak konfigurovat AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: dd6d6986b23c8adcc98fe713bacf32fb5bf8b4b6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915559"
---
# <a name="configure-sync-features"></a>Konfigurace funkce synchronizace

Azure AD připojit obsahuje několik funkcí, které jsou ve výchozím nastavení povolena, nebo můžete povolit později. Některé funkce vyžadují další konfiguraci v konkrétním prostředí.
  
- Omezení [filtrování](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) objektů jsou synchronizovány do Azure AD. Ve výchozím nastavení, všechny uživatelé, kontakty, skupiny a Windows 10 účtů počítače synchronizovány. Můžete zahrnout nebo vyloučit objekty založené na doménách, organizačních jednotkách nebo jiných atributech. 
    
- [Synchronizace hesel hash](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizuje hodnotu hash hesla adresářové služby Active Directory v prostorách Azure AD. To umožňuje správu hesel na jednom místě, ale použít stejné heslo v obou místních a cloudových prostředí. Vzhledem k tomu, že služba Active Directory je autoritativní zdroj, můžete použít vlastní zásady hesla. 
    
- [Obnovení hesla samoobslužné (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) umožňuje uživatelům obnovit hesla v cloudu přitom stále použít místní zásady hesla. 
    
- [Zpětný zápis zařízení](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) umožňuje registrovaným zařízením v Azure AD pro zápis zpět do služby Active Directory v prostorách tak slouží pro podmíněný přístup. 
    
- [Zabránit náhodnému odstranění](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) je povoleno ve výchozím nastavení pomáhá zabránit odstranění příliš mnoho souběžných objektu (více než 500 objektů na synchronizaci). Můžete změnit toto nastavení podle potřeb vaší organizace. 
    
- [Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) je povolena ve výchozím nastavení pro expresní instalace a pomáhá zajistit, že vaše verze Azure AD připojit, je vždy aktuální. 
    


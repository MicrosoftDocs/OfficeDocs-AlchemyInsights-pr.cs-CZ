---
title: Zásady uchovávání informací v Exchange Admin Center nefunguje
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 73e8db432afccb73b872ec7a3ce84c25f1ba7f25
ms.sourcegitcommit: ca06ef831226d629de3057a0df85e017b80f3356
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/08/2019
ms.locfileid: "29786763"
---
# <a name="retention-policies-in-exchange-admin-center"></a>Zásady uchovávání informací v Exchange Admin Center

 **Vydání:** Nově vytvořené nebo aktualizované uchovávání zásady v Exchange Admin Center nejsou platné pro poštovní schránky nebo položky nejsou přesunuty do poštovní schránky archivu nebo odstraněny. 
  
 **Příčiny:**
  
- To může být, vzhledem k tomu, že na **Pomocníka spravované složky** nebyl zpracován poštovní schránce uživatele. Spravované složky pomocníka pokusí zpracovat každou poštovní schránku v organizaci založené na cloudu každých sedm dní. Pokud změníte značku uchovávání informací nebo použít jiné zásady uchovávání informací poštovní schránky, můžete počkat, dokud spravované složky pomáhají zpracovává poštovní schránky nebo můžete spustit rutinu Start-ManagedFolderAssistant spuštění spravované složky Pomocníka pro zpracování konkrétní poštovní schránka. Spuštění této rutiny je užitečné pro testování a odstraňování problémů nastavení značky uchovávání informací nebo zásady uchovávání informací. Další informace naleznete [spouštět spravované složky pomocníka](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).
    
  - **Řešení:** Spusťte následující příkaz ke spuštění spravované složky Pomocníka pro určité poštovní schránky: 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- Může to dojít také v případě **RetentionHold** byla **povolena** v poštovní schránce. Pokud poštovní schránka byla umístěna na RetentionHold, zásady uchovávání informací schránky nebudou zpracovány během této doby. Pro další informace o nastavení viz RetentionHold: [Podržte uchovávání informací poštovní schránky](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).
    
    **Řešení:**
    
  - Zkontrolujte stav nastavení RetentionHold na určité poštovní schránky v [prostředí powershell EXO](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - Spusťte následující příkaz **Zakázat** RetentionHold na určité poštovní schránky: 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - Nyní spusťte znovu spravované složky pomocníka:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 **Poznámka:** Pokud poštovní schránky je menší než 10 MB, spravované složky pomocníka nebude automatické zpracování poštovní schránky. 
  


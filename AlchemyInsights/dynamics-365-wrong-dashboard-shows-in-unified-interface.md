---
title: Dynamics 365 - chybný řídicí panel se zobrazí v rozhraní Unified Dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 6edf6fbae0174f3fa4d635c7a99e7daae1243b60
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747219"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a>Chybný řídicí panel se zobrazí v rozhraní unified Dynamics 365

Existuje několik důvodů, proč se může zobrazit jiný řídicí panel než ten, který můžete očekávat:

## <a name="the-user-has-set-a-user-default-dashboard"></a>Uživatel nastavil výchozí uživatelský řídicí panel 

Obvykle můžete identifikovat uživatele výchozí řídicí panel je nastavena, je-li na tlačítko **Nastavit jako výchozí** řídicí panel panel příkazů nezobrazuje. Uživatelský řídicí panel Výchozí přepíše všechny ostatní výchozí řídicí panely, i když není v aktuální aplikaci app uživatele výchozí řídicí panel.

Použijte následující řešení Chcete-li zrušit jejich výchozího řídicího panelu.

1. Vytvořte nový osobní řídicí panel.

2. Nastavte tento nový řídicí panel jako výchozí nastavení uživatele.

3. Odstraňte tento řídicí panel.

## <a name="the-dashboard-is-set-in-the-sitemap"></a>Řídicí panel je nastavena v mapě stránek

Mohou být nastavena výchozí řídicí panel organizace řídicího panelu vyberete a zvolíte "Nastavit jako výchozí" v části vlastní nastavení systému. Ale podle mapy webu Návrhář řídicího panelu má přednost tento řídicí panel, pokud má uživatel přístup k němu.

Pokud chcete, aby uživatelé řídicího panelu, které jste nastavili jako výchozí organizace naleznete v tématu, můžete buď:

* Nastavit tento řídicí panel v mapě stránek

* Odebrat přístup k řídicího panelu definované mapy webu pro uživatele

---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4d911c319c3e8e327f9b3af3ba67816e646bc468
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32399584"
---
# <a name="how-to-disable-external-groups"></a>Jak zakázat externí skupiny

Yammer, že externí zasílání platí pravidla dopravní Exchange (ETRs), sadu ovládacích prvků aktivní, chcete-li zabránit sdílení informací společnosti. S cílem zabránit vytváření externích skupin uživatelů, je třeba nakonfigurovat pravidlo Exchange transport (ETR) a potom nakonfigurujte Yammer pomocí pravidla Exchange Transport blokovat externí zasílání zpráv. 
  
Jakmile vytvoříte pravidlo v Exchange Online admin center, ETR, které chcete použít v Yammer nastavit takto:
  
- Přihlaste se k Yammer ověřené admin a v **Yammer admin center**, přejděte na příkaz C **odesílaných a zabezpečení \> nastavení zabezpečení.**
    
- V části **Externí zasílání zpráv**, vyberte **v Yammer vynutit Exchange Online Exchange Transport pravidla (ETRs).**
    
- Zvolte **Uložit**. 
    
Další informace naleznete v tématu [řízení externí zasílání zpráv v síti Yammer pomocí pravidla Exchange Transport](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  


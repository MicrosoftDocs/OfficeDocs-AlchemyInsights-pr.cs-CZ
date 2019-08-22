---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4683a71438ec31f9e9211404a9c66c4e45e0e1df
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36540894"
---
# <a name="how-to-disable-external-groups"></a>Jak zakázat externí skupiny

Yammer, že externí zasílání platí pravidla dopravní Exchange (ETRs), sadu ovládacích prvků aktivní, chcete-li zabránit sdílení informací společnosti. S cílem zabránit vytváření externích skupin uživatelů, je třeba nakonfigurovat pravidlo Exchange transport (ETR) a potom nakonfigurujte Yammer pomocí pravidla Exchange Transport blokovat externí zasílání zpráv.
  
Jakmile vytvoříte pravidlo v Exchange Online admin center, ETR, které chcete použít v Yammer nastavit takto:
  
- Přihlaste se k Yammer ověřené admin a v **Yammer admin center**, přejděte na příkaz C **obsahu a zabezpečení \> nastavení zabezpečení.**

- V části **Externí zasílání zpráv**, vyberte **v Yammer vynutit Exchange Online Exchange Transport pravidla (ETRs).**

- Zvolte **Uložit**.

Další informace naleznete v tématu [řízení externí zasílání zpráv v síti Yammer pomocí pravidla Exchange Transport](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  
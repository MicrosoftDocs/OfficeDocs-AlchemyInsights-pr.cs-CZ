---
title: Zapnutí technologie NDI
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004403"
- "7947"
ms.openlocfilehash: ea694898baffa50fca71957175eba3664dece44e
ms.sourcegitcommit: 112f18dce8257b98fab32d44910ee879efb44cb8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/21/2021
ms.locfileid: "49935082"
---
# <a name="turn-on-ndi-technology"></a>Zapnutí technologie NDI

Technologie NDI vyžaduje pro uživatele dva kroky:

1. Správce tenanta musí povolit vlastnost AllowNDIStreaming v CsTeamsMeetingPolicy.

    `Set-CsTeamsMeetingPolicy -Identity MEETING_POLICY -AllowNDIStreaming $true`

2. Po vyplnění této změny musí koncový uživatel pro svého konkrétního klienta zapnout technologii NDI® > **oprávnění.**

Další informace najdete v článku Používání technologie [NDI v Microsoft Teams.](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings)

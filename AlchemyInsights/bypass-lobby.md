---
title: Obejít lobby
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: 6632bb0c09c7ce99f14cd55582025b37a846369d
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "37654249"
---
# <a name="control-lobby-settings-and-level-of-participation"></a>Řídit nastavení lobby a úroveň účasti

Pokud chcete všem uživatelům, včetně telefonických, externích a anonymních uživatelů, umožnit obejít lobby, můžete k tomu použít prostředí PowerShell. Zde je příklad úpravy globálních zásad schůzky pro vaši organizaci:

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

Tato rutina v současné době vyžaduje použití modulu Skype for Business PowerShell. Chcete-li nastavit použití této rutiny, podívejte se na [správu zásad prostřednictvím prostředí PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).

Můžete vytvořit novou zásadu, kterou pak budete muset použít pro uživatele. Pokud upravíte globální zásadu, bude automaticky použita i pro uživatele. U každé změny zásad je třeba vyčkat nejméně 4 hodiny a až 24 hodin, aby se zásady projevily.

Před provedením těchto změn si přečtěte následující dokumentaci, abyste přesně pochopili, co to umožňuje.

## <a name="understanding-teams-meeting-lobby-policy-controls"></a>Principy týmů, které se řídí zásadami lobby

- [Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.

- [Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.

- [Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .

- [Umožnit organizátorům přepsání nastavení lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**brzy přijde**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **Povolit telefonické připojení uživatelům obejít lobby** při plánování nové schůzky.

**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) .

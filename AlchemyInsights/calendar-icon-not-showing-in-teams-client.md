---
title: Nezobrazující se ikona kalendáře v klientovi Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001219"
- "4375"
ms.openlocfilehash: f30cd5bda62756cf6b912ed150b4e59e7ca4d85d
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/14/2020
ms.locfileid: "47684691"
---
# <a name="calendar-icon-not-showing-in-teams-client"></a><span data-ttu-id="7aebd-102">Nezobrazující se ikona kalendáře v klientovi Teams</span><span class="sxs-lookup"><span data-stu-id="7aebd-102">Calendar icon not showing in Teams client</span></span>

<span data-ttu-id="7aebd-103">Karta kalendáře v Teams vyžaduje přístup k poštovní schránce Exchange prostřednictvím webových služeb Exchange.</span><span class="sxs-lookup"><span data-stu-id="7aebd-103">The Calendar Tab in Teams requires access to an Exchange mailbox via Exchange Web Services.</span></span> <span data-ttu-id="7aebd-104">Poštovní schránka Exchange může být online nebo místní.</span><span class="sxs-lookup"><span data-stu-id="7aebd-104">The Exchange mailbox can be Online or On-Premises.</span></span> <span data-ttu-id="7aebd-105">V případě online uživatelů, kteří nevidí kartu Kalendář, zkontrolujte, jestli [mají licenci pro poštovní schránku Exchange Online a že poštovní schránka je povolena](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="7aebd-105">For Online users who do not see the Calendar Tab, make sure they [are licensed for an Exchange Online mailbox and the mailbox is enabled](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).</span></span>

<span data-ttu-id="7aebd-106">Pokud má uživatel v Exchange Online platnou poštovní schránku, ale karta Kalendář se pořád nezobrazuje, je možné, že dochází k potížím se sítí.</span><span class="sxs-lookup"><span data-stu-id="7aebd-106">If the user has a valid mailbox in Exchange Online, but still cannot see the Calendar tab, you may be experiencing a network issue.</span></span> <span data-ttu-id="7aebd-107">U ovlivněných uživatelů použijte nástroj [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) a spusťte **testy připojení Webových služeb systému Microsoft Exchange**.</span><span class="sxs-lookup"><span data-stu-id="7aebd-107">Use the [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) and run the **Microsoft Exchange Web Services Connectivity Tests** for the impacted user.</span></span>

<span data-ttu-id="7aebd-108">Nakonec zaškrtnutím políčka [Aplikace Teams – zásady nastavení aplikací](https://admin.teams.microsoft.com/policies/app-setup) zajistíte, že se aplikace Kalendář neodebere ze zásad použitých u uživatele (nejpravděpodobněji **Globální (výchozí nastavení celé organizace)**.</span><span class="sxs-lookup"><span data-stu-id="7aebd-108">Finally check the [Teams Apps – App setup policies](https://admin.teams.microsoft.com/policies/app-setup) to ensure the Calendar app has not been removed from the policy applied to the user (most likely the **Global (Org-wide default)**.</span></span>

<span data-ttu-id="7aebd-109">Pokud jsou vaši uživatelé místní, budete muset ověřit, jestli je hybridní konfigurace v pořádku.</span><span class="sxs-lookup"><span data-stu-id="7aebd-109">If your users are homed On-Premises, you need to confirm your Hybrid configuration is healthy.</span></span> <span data-ttu-id="7aebd-110">K řešení potíží použijte [průvodce hybridní konfigurací](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent).</span><span class="sxs-lookup"><span data-stu-id="7aebd-110">Use the [Hybrid Configuration Wizard](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent) to troubleshoot.</span></span>

<span data-ttu-id="7aebd-111">Poznámka: [Teams vyžaduje Exchange 2016 CU3 nebo novější](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span><span class="sxs-lookup"><span data-stu-id="7aebd-111">Note that [Teams requires Exchange 2016 CU3 or higher](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span></span>

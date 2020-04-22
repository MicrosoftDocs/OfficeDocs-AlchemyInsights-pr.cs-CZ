---
title: Vyřazení starších nástrojů eDiscovery
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: 262cca0feee17d1f929a5a94a4dd6c1ec317f6ec
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/21/2020
ms.locfileid: "43650561"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="d18cf-102">Vyřazení starších nástrojů eDiscovery</span><span class="sxs-lookup"><span data-stu-id="d18cf-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="d18cf-103">V důsledku nové a vylepšené funkce eDiscovery v Centru dodržování předpisů Microsoftu 365 budou v nadcházejících měsících vyřazeny následující starší nástroje a příkazy eDiscovery:</span><span class="sxs-lookup"><span data-stu-id="d18cf-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="d18cf-104">[Místní eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) a [místní blokování v](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) Centru pro správu Exchange.</span><span class="sxs-lookup"><span data-stu-id="d18cf-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="d18cf-105">Rutiny prostředí Exchange Online PowerShell, které podporují místní eDiscovery a místní blokování.</span><span class="sxs-lookup"><span data-stu-id="d18cf-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="d18cf-106">(Tyto rutiny jsou souhrnně identifikovány jako rutiny \*-MailboxSearch.) To zahrnuje následující rutiny:</span><span class="sxs-lookup"><span data-stu-id="d18cf-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="d18cf-107">Nové poštovní schránkyHledání</span><span class="sxs-lookup"><span data-stu-id="d18cf-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="d18cf-108">Hledání start-poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="d18cf-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="d18cf-109">Stop-MailboxHledání</span><span class="sxs-lookup"><span data-stu-id="d18cf-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="d18cf-110">Set-MailboxHledání</span><span class="sxs-lookup"><span data-stu-id="d18cf-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="d18cf-111">Rutina [Vyhledávací poštovní schránka](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) v prostředí Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="d18cf-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="d18cf-112">Následující operace v rozhraní API webových služeb exchange:</span><span class="sxs-lookup"><span data-stu-id="d18cf-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="d18cf-113">GetSearchablePoštovní schránky</span><span class="sxs-lookup"><span data-stu-id="d18cf-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="d18cf-114">Schránky SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="d18cf-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="d18cf-115">Schránky GetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="d18cf-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="d18cf-116">Rozšířené eDiscovery v1.0</span><span class="sxs-lookup"><span data-stu-id="d18cf-116">Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="d18cf-117">**Časová osa odchodu do důchodu**:</span><span class="sxs-lookup"><span data-stu-id="d18cf-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="d18cf-118">1. dubna 2020: Nebudete moci vytvářet nová hledání a blokování, ale stále můžete spouštět, upravovat a odstraňovat stávající hledání na vlastní nebezpečí.</span><span class="sxs-lookup"><span data-stu-id="d18cf-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="d18cf-119">Podpora společnosti Microsoft již nebude podporovat místní zjišťování eDiscovery & blokování v EAC.</span><span class="sxs-lookup"><span data-stu-id="d18cf-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="d18cf-120">1. července 2020: Funkce Na místě, & eDiscovery, bude v EAC umístěna do režimu jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="d18cf-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="d18cf-121">To znamená, že budete moci odebrat pouze existující vyhledávání a blokování.</span><span class="sxs-lookup"><span data-stu-id="d18cf-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="d18cf-122">**Další informace naleznete v tématu**:</span><span class="sxs-lookup"><span data-stu-id="d18cf-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="d18cf-123">Migrace starších vyhledávání eDiscovery a jejich držení do Centra dodržování předpisů Microsoftu 365</span><span class="sxs-lookup"><span data-stu-id="d18cf-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="d18cf-124">Vyřazení starších nástrojů eDiscovery</span><span class="sxs-lookup"><span data-stu-id="d18cf-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="d18cf-125">Časté otázky týkající se místního zjišťování eDiscovery a místních blokování</span><span class="sxs-lookup"><span data-stu-id="d18cf-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)




---
title: 182 pro diagnostiku a vyřešení problémů s ověřováním Outlooku spusťte příkaz SaRA.
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "182"
- "1800012"
ms.assetid: a3a5ea91-6989-4616-9290-c7b24484e8c8
ms.openlocfilehash: aa1e831eac829f3bd35f34e2fbe34923c5af0d3a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/15/2020
ms.locfileid: "47802014"
---
# <a name="use-sara-to-diagnose-and-resolve-outlook-authentication-issues"></a><span data-ttu-id="a6c7d-102">Použití nástroje SaRA k diagnostice a řešení problémů s ověřováním v Outlooku</span><span class="sxs-lookup"><span data-stu-id="a6c7d-102">Use SaRA to diagnose and resolve Outlook authentication issues</span></span>

<span data-ttu-id="a6c7d-103">**Poznámka**: Zkontrolujte, jestli je ve vaší organizaci povolené [výchozí nastavení zabezpečení](https://aka.ms/securitydefaults) .</span><span class="sxs-lookup"><span data-stu-id="a6c7d-103">**Note**: Please check to see whether [security defaults](https://aka.ms/securitydefaults) is enabled for your organization.</span></span> <span data-ttu-id="a6c7d-104">Pokud byl váš tenant vytvořen po 21. října 2019 a vaše Outlook vás opakovaně žádá o zadání hesla, můžete mít ve vašem tenantovi povolené **výchozí nastavení zabezpečení** .</span><span class="sxs-lookup"><span data-stu-id="a6c7d-104">If your tenant was created after October 21st, 2019 and your Outlook is repeatedly asking you for a password, you may have **security defaults** enabled in your tenant.</span></span>

<span data-ttu-id="a6c7d-105">Důrazně doporučujeme, abyste v případě, že Outlook průběžně vyzývá k zadání hesla, zaznamenali v počítači chybu Diagnostika [svého hesla](https://aka.ms/SaRA-OutlookPwdPrompt-Alchemy) .</span><span class="sxs-lookup"><span data-stu-id="a6c7d-105">We highly recommend you use the [Outlook keeps asking for my password](https://aka.ms/SaRA-OutlookPwdPrompt-Alchemy) diagnostic on the affected machine to troubleshoot issues where Outlook continually prompts for a password.</span></span> <span data-ttu-id="a6c7d-106">Tento [diagnostický](https://diagnostics.office.com/#/) Nástroj pro diagnostiku provádí automatizované kontroly a vrací možná řešení, která umožňují řešit všechny zjištěné problémy.</span><span class="sxs-lookup"><span data-stu-id="a6c7d-106">This [SaRA](https://diagnostics.office.com/#/) diagnostic does automated checks and returns possible solutions for you to use to address any detected issues.</span></span>

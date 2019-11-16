---
title: Problémy s MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: a415116b9ba437cb13426896119cd1b40d9ab491
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768830"
---
# <a name="issues-with-azure-mfa"></a><span data-ttu-id="6001c-102">Problémy s Azure MFA</span><span class="sxs-lookup"><span data-stu-id="6001c-102">Issues with Azure MFA</span></span>
<span data-ttu-id="6001c-103">Existuje několik možností, jak zkontrolovat, zda se uživatelé nemohou přihlásit pomocí vícefaktorového ověřování (MFA).</span><span class="sxs-lookup"><span data-stu-id="6001c-103">There are a couple of things to check if users cannot log in using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="6001c-104">Ohrožený uživatel může být blokován na portálu Azure Active Directory Portal.</span><span class="sxs-lookup"><span data-stu-id="6001c-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="6001c-105">V takovém případě budou pokusy o ověření pro tohoto konkrétního uživatele automaticky odepřeny.</span><span class="sxs-lookup"><span data-stu-id="6001c-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="6001c-106">Chcete-li je odblokovat, postupujte podle kroků v tomto článku.</span><span class="sxs-lookup"><span data-stu-id="6001c-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="6001c-107">Pokud odblokování uživateli nepomůže nebo uživatel není blokován, můžete se pokusit resetovat MFA pro uživatele a znovu projít procesem zápisu.</span><span class="sxs-lookup"><span data-stu-id="6001c-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="6001c-108">Postupujte prosím podle pokynů v tomto článku.</span><span class="sxs-lookup"><span data-stu-id="6001c-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="6001c-109">V případě, že jste poprvé povolili službu MFA a uživatelé se nemohou přihlásit k jiným klientům než prohlížečům, jako je například aplikace Outlook, Skype atd., není v odběru O365 pravděpodobně povolena služba AD Al (Active Directory Authentication Library).</span><span class="sxs-lookup"><span data-stu-id="6001c-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="6001c-110">V takovém případě se budete muset připojit k serveru Exchange Online PowerShell a spustit tuto rutinu:  *set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*</span><span class="sxs-lookup"><span data-stu-id="6001c-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>
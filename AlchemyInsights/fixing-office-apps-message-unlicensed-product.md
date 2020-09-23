---
title: Office nejde aktivovat
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
- "2000023"
- "3509"
ms.openlocfilehash: e052c18eae035ff05c70a223f6d8a2eab875b2c9
ms.sourcegitcommit: 57102d7daf32f370cab84dba342819a1ad5cb261
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/23/2020
ms.locfileid: "48236082"
---
# <a name="unable-to-activate-office"></a><span data-ttu-id="dfa79-102">Office nejde aktivovat</span><span class="sxs-lookup"><span data-stu-id="dfa79-102">Unable to activate Office</span></span>

- <span data-ttu-id="dfa79-103">Zkontrolujte, jestli platnost vašeho předplatného vypršela.</span><span class="sxs-lookup"><span data-stu-id="dfa79-103">Check if your subscription status has expired.</span></span>
- <span data-ttu-id="dfa79-104">Zkontrolujte, jestli máte předplatné, které umožňuje klientské licence, třeba Office 365 Business nebo Business Premium, a [Zkontrolujte, jestli má uživatel přiřazenou licenci](https://docs.microsoft.com/microsoft-365/admin/subscriptions-and-billing/assign-licenses-to-users).</span><span class="sxs-lookup"><span data-stu-id="dfa79-104">Ensure you have a subscription that allows client licenses, such as Office 365 Business or Business Premium, and [ensure the user has a license assigned](https://docs.microsoft.com/microsoft-365/admin/subscriptions-and-billing/assign-licenses-to-users).</span></span>
- <span data-ttu-id="dfa79-105">Zkontrolujte, jestli je uživatel přihlášený k Office pomocí stejného účtu, který má přiřazenou licenci.</span><span class="sxs-lookup"><span data-stu-id="dfa79-105">Ensure the user is signing into Office with the same account that has the license assigned.</span></span>
- <span data-ttu-id="dfa79-106">Podívejte se na [stránku stavu služeb Office 365](https://docs.microsoft.com/office365/enterprise/view-service-health) a zjistěte, jestli se vyskytly nějaké problémy.</span><span class="sxs-lookup"><span data-stu-id="dfa79-106">Check the [Office 365 Service Health page](https://docs.microsoft.com/office365/enterprise/view-service-health) to see if there are any known problems with the service.</span></span>
- <span data-ttu-id="dfa79-107">Zkontrolujte nastavení brány firewall, antivirového softwaru a proxy serveru a ověřte, že neblokují aplikace Microsoft 365 přístup k Internetu.</span><span class="sxs-lookup"><span data-stu-id="dfa79-107">Check your firewall, antivirus software and proxy settings to confirm that they are not blocking Microsoft 365 apps access to the internet.</span></span> <span data-ttu-id="dfa79-108">Přečtěte si [Adresy URL a rozsahy IP adres pro Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges "Adresy URL a rozsahy IP adres pro Office 365").</span><span class="sxs-lookup"><span data-stu-id="dfa79-108">Please see [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges "Office 365 URLs and IP address ranges").</span></span>

<span data-ttu-id="dfa79-109">**Tip** V počítačích s Windows můžeme diagnostikovat a automaticky opravovat několik běžných problémů s přihlášením k Office.</span><span class="sxs-lookup"><span data-stu-id="dfa79-109">**Tip** On Windows machines, we can diagnose and automatically fix several common Office sign-in issues for you.</span></span> <span data-ttu-id="dfa79-110">Stáhněte si a spusťte nástroj  **[Microsoft Support and Recovery Assistant](https://aka.ms/SaRA-OfficeSignInScenario)** , abyste mohli používat náš automatizovaný nástroj.</span><span class="sxs-lookup"><span data-stu-id="dfa79-110">Download and run the  **[Microsoft Support and Recovery Assistant](https://aka.ms/SaRA-OfficeSignInScenario)** to use our automated tool.</span></span>

<span data-ttu-id="dfa79-111">Při řešení problémů postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="dfa79-111">Use the following troubleshooting actions:</span></span>

- <span data-ttu-id="dfa79-112">Otevřete aplikaci Office a [odhlaste se](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) od všech existujících uživatelských účtů.</span><span class="sxs-lookup"><span data-stu-id="dfa79-112">Open an Office app, and [sign out](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) of any existing user accounts.</span></span> <span data-ttu-id="dfa79-113">[Odeberte](https://docs.microsoft.com/microsoft-365/admin/manage/remove-licenses-from-users) a [znovu přiřaďte](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) licence Office, a potom [se přihlaste k Office](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) pomocí ovlivněného uživatelského účtu.</span><span class="sxs-lookup"><span data-stu-id="dfa79-113">[Remove](https://docs.microsoft.com/microsoft-365/admin/manage/remove-licenses-from-users) and [re-assign](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) Office license, and then [sign into Office](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) using the affected user account.</span></span>
- <span data-ttu-id="dfa79-114">Spusťte [Poradce při potížích s aktivací](https://aka.ms/SARA-OfficeActivation-Alchemy).</span><span class="sxs-lookup"><span data-stu-id="dfa79-114">Run the [Activation Troubleshooter](https://aka.ms/SARA-OfficeActivation-Alchemy)</span></span>
- <span data-ttu-id="dfa79-115">[Resetujte stav aktivace Office](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state "Obnovení stavu aktivace Office").</span><span class="sxs-lookup"><span data-stu-id="dfa79-115">[Reset Office activation state](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state "Reset Office activation state")</span></span>
- <span data-ttu-id="dfa79-116">[Proveďte online opravu Office](https://support.office.com/Article/7821d4b6-7c1d-4205-aa0e-a6b40c5bb88b?wt.mc_id=Alchemy_ClientDIA).</span><span class="sxs-lookup"><span data-stu-id="dfa79-116">[Perform an Online Repair of Office](https://support.office.com/Article/7821d4b6-7c1d-4205-aa0e-a6b40c5bb88b?wt.mc_id=Alchemy_ClientDIA)</span></span>

<span data-ttu-id="dfa79-117">Další řešení problémů najdete tady:</span><span class="sxs-lookup"><span data-stu-id="dfa79-117">For additional troubleshooting solutions, see:</span></span>  

- [<span data-ttu-id="dfa79-118">Chyby typu Nelicencovaný produkt a chyby aktivace v Office</span><span class="sxs-lookup"><span data-stu-id="dfa79-118">Unlicensed Product and activation errors in Office</span></span>](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380?wt.mc_id=Alchemy_ClientDIA)
- [<span data-ttu-id="dfa79-119">Chyba „Je nám líto, ale nemůžeme se připojit k vašemu účtu. Zkuste to prosím znovu později.“ při aktivaci Office</span><span class="sxs-lookup"><span data-stu-id="dfa79-119">"Sorry, we can't connect to your account. Please try again later" error when you activate Office</span></span>](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365)
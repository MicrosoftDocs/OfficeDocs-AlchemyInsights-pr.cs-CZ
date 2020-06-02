---
title: Oprava aplikací Office Nemůžu najít přidruženou zprávu o licencích Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3421"
- "9001426"
ms.openlocfilehash: 887be4bee2bd1562bdc3b29783e9deafe47d8d57
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505860"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a><span data-ttu-id="d458a-102">Oprava zprávy O opravě aplikací Office "Nelze najít přidružené licence office"</span><span class="sxs-lookup"><span data-stu-id="d458a-102">Fixing the Office apps "Couldn't find office licenses associated" message</span></span>

<span data-ttu-id="d458a-103">Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="d458a-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="d458a-104">Zkontrolujte nastavení brány firewall, antivirového softwaru a proxy serveru a ověřte, zda neblokují přístup k Internetu k aplikacím Office.</span><span class="sxs-lookup"><span data-stu-id="d458a-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="d458a-105">Viz [Microsoft 365 URL a rozsahy IP adres](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="d458a-105">See [Microsoft 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>
2. <span data-ttu-id="d458a-106">Odeberte a [znovu přiřaďte licenci Office](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) pro postiženého uživatele.</span><span class="sxs-lookup"><span data-stu-id="d458a-106">Remove and [reassign the Office license](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) for the affected user.</span></span> 
3. <span data-ttu-id="d458a-107">Otevřete aplikaci Office a [odhlaste se od](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) všech existujících uživatelských účtů.</span><span class="sxs-lookup"><span data-stu-id="d458a-107">Open an Office app and [sign out](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) of any existing user accounts.</span></span>
4. <span data-ttu-id="d458a-108">Přejděte na Nastavení systému Windows > **účty**  >  **e-mail & účtů**a odeberte všechny pracovní účty kromě ovlivněného účtu.</span><span class="sxs-lookup"><span data-stu-id="d458a-108">Go to Windows Settings > **Accounts** > **Email & accounts**, and remove all work accounts except the affected account.</span></span>
5. <span data-ttu-id="d458a-109">Přejděte na Nastavení systému Windows > **Accounts**  >  **účty Přístup k práci nebo škole**a odpojte všechny pracovní účty kromě ovlivněného účtu.</span><span class="sxs-lookup"><span data-stu-id="d458a-109">Go to Windows Settings > **Accounts** > **Access work or school**, and disconnect all work accounts except the affected account.</span></span>
6. <span data-ttu-id="d458a-110">Resetujte stav aktivace Office.</span><span class="sxs-lookup"><span data-stu-id="d458a-110">Reset the Office activation state.</span></span> <span data-ttu-id="d458a-111">[Přečtěte si, jak](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).</span><span class="sxs-lookup"><span data-stu-id="d458a-111">[Learn how](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).</span></span>
7. <span data-ttu-id="d458a-112">[Přihlaste se](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) pomocí ovlivněného uživatelského účtu.</span><span class="sxs-lookup"><span data-stu-id="d458a-112">[Sign in](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) using the affected user account.</span></span>

<span data-ttu-id="d458a-113">Další řešení potíží najdete [v tématu Chyby nelicencovaného produktu a aktivace v Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span><span class="sxs-lookup"><span data-stu-id="d458a-113">For additional troubleshooting solutions, see [Unlicensed Product and activation errors in Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span></span>
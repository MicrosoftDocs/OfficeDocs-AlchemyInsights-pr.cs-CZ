---
title: Určení adresy IP a klient z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: a91778c006531371b85116f5c97485d42e6cc5be
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35382946"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="f62be-102">Určení adresy IP a klient z protokolů auditování</span><span class="sxs-lookup"><span data-stu-id="f62be-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="f62be-103">Adresy IP, která odpovídá činnosti uživatelem nebo správcem, je uveden v protokoly auditu.</span><span class="sxs-lookup"><span data-stu-id="f62be-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="f62be-104">Informace o klientovi je také zaznamenána.</span><span class="sxs-lookup"><span data-stu-id="f62be-104">The client information is also logged.</span></span> <span data-ttu-id="f62be-105">Zde jsou kroky k identifikaci těchto informací</span><span class="sxs-lookup"><span data-stu-id="f62be-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="f62be-106">Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="f62be-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="f62be-107">Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.</span><span class="sxs-lookup"><span data-stu-id="f62be-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="f62be-108">Pokud vás zajímají konkrétní aktivity, vyberte ji ze seznamu **aktivit** .</span><span class="sxs-lookup"><span data-stu-id="f62be-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="f62be-109">Pokud ne, budou vráceny všechny aktivity pro vybraného uživatele (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="f62be-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="f62be-110">**Poznámka**: některé činnosti nemusí být k dispozici v nabídce **činností** ; však ty položky auditu bude vrácena, pokud je **Zobrazit výsledky pro všechny činnosti** (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="f62be-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="f62be-111">Zadejte uživatelské jméno do pole **Uživatelé** a vyberte příslušné období aktivity klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="f62be-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="f62be-112">Ve výsledcích se zobrazí adresu IP pro tuto činnost v podokně výsledků.</span><span class="sxs-lookup"><span data-stu-id="f62be-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="f62be-113">Vyberte záznam auditu zobrazíte podrobné informace vždy **Podrobnosti** (například klienta, uživatel, který provedl akci, atd.).</span><span class="sxs-lookup"><span data-stu-id="f62be-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="f62be-114">Další informace naleznete v tématu [vyhledání adresy IP počítače pro přístup k ohrožení zabezpečení účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="f62be-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>

---
title: Problémy výkonu-služby SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719510"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="955d8-102">Služby SharePoint nebo OneDrive pomalu nedostupný nebo není k dispozici pro více uživatelů</span><span class="sxs-lookup"><span data-stu-id="955d8-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="955d8-103">Pokud není k dispozici pro více uživatelů, kteří dříve měl přístup na OneDrive nebo SharePoint Server, může se jednat o problém dočasnou službu.</span><span class="sxs-lookup"><span data-stu-id="955d8-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="955d8-104">[Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="955d8-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="955d8-105">Přidat a licencovat uživatele</span><span class="sxs-lookup"><span data-stu-id="955d8-105">Add and license the user</span></span>

<span data-ttu-id="955d8-106">Zajistit, že můžete [přiřadit licence pro uživatele ve službách Office 365 pro firmy](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="955d8-106">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>


## <a name="assign-permissions"></a><span data-ttu-id="955d8-107">Přiřazení oprávnění</span><span class="sxs-lookup"><span data-stu-id="955d8-107">Assign Permissions</span></span>

<span data-ttu-id="955d8-108">Pokud uživateli byla přiřazena licence služby Sharepoint je stále zobrazuje zpráva o odepření přístupu, ujistěte se, že mají [odpovídající úroveň oprávnění](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) přiřazena.</span><span class="sxs-lookup"><span data-stu-id="955d8-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) assigned.</span></span>

## <a name="consider-using-the-access-request-feature"></a><span data-ttu-id="955d8-109">Zvažte použití funkce žádost o přístup</span><span class="sxs-lookup"><span data-stu-id="955d8-109">Consider using the access request feature</span></span>

<span data-ttu-id="955d8-110">[Funkce žádost o přístup](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) umožňuje uživatelům požadovat přístup k obsahu, který aktuálně nemají oprávnění k zobrazení.</span><span class="sxs-lookup"><span data-stu-id="955d8-110">The [access request feature](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

## <a name="allow-custom-script-may-cause-access-denied-issues"></a><span data-ttu-id="955d8-111">Povolit vlastní skript může způsobit, že přístup byl odepřen problémy</span><span class="sxs-lookup"><span data-stu-id="955d8-111">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="955d8-112">Existují určité scénáře *vlastního skriptu povolit* funkce může kde předkládány odepření přístupu.</span><span class="sxs-lookup"><span data-stu-id="955d8-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="955d8-113">Seznam funkcí, které jsou ovlivněny, důležité informace o zabezpečení a možnost zakázat funkci.</span><span class="sxs-lookup"><span data-stu-id="955d8-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="955d8-114">Navštivte [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="955d8-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>

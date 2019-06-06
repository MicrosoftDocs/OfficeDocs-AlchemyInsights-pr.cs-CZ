---
title: Poradce při potížích s zprávy o odepření přístupu
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 5958ad06ca905f713b5f56aa5c536e95a485f01c
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735731"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="5c098-102">Poradce při potížích s zprávy o odepření přístupu</span><span class="sxs-lookup"><span data-stu-id="5c098-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="5c098-103">Pokud se zobrazuje zpráva o odepření při pokusu o procházení webu služby Sharepoint Online přístupu, viz prosím pod články.</span><span class="sxs-lookup"><span data-stu-id="5c098-103">If you are receiving an access denied message when attempting to browse a Sharepoint Online site, please see the below articles.</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="5c098-104">Přidat a licencovat uživatele</span><span class="sxs-lookup"><span data-stu-id="5c098-104">Add and License the user</span></span>

<span data-ttu-id="5c098-105">Zajistit, že můžete [přiřadit licence pro uživatele ve službách Office 365 pro firmy](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="5c098-105">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>

<span data-ttu-id="5c098-106">Přiřazení oprávnění</span><span class="sxs-lookup"><span data-stu-id="5c098-106">Assign Permissions</span></span>

<span data-ttu-id="5c098-107">Pokud uživateli byla přiřazena licence služby Sharepoint je stále zobrazuje zpráva o odepření přístupu, ujistěte se, že mají [odpovídající úroveň oprávnění přiřazena](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="5c098-107">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level assigned](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>

<span data-ttu-id="5c098-108">Zvažte použití funkce žádost o přístup</span><span class="sxs-lookup"><span data-stu-id="5c098-108">Consider using the access request feature</span></span>

<span data-ttu-id="5c098-109">[Žádost o přístup k](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) funkci umožňuje uživatelům požadovat přístup k obsahu, který aktuálně nemají oprávnění k zobrazení.</span><span class="sxs-lookup"><span data-stu-id="5c098-109">The [access request](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) feature allows people to request access to content that they do not currently have permission to see.</span></span> 

<span data-ttu-id="5c098-110">Povolit vlastní skript může způsobit, že přístup byl odepřen problémy</span><span class="sxs-lookup"><span data-stu-id="5c098-110">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="5c098-111">Existují některé scénáře, kde funkce "Povolit vlastní skript" mohou být předkládány odepření přístupu.</span><span class="sxs-lookup"><span data-stu-id="5c098-111">There are certain scenarios where the "Allow custom script" feature may be presenting an access denied.</span></span> <span data-ttu-id="5c098-112">Seznam funkcí, které jsou ovlivněny, důležité informace o zabezpečení a možnost zakázat funkci.</span><span class="sxs-lookup"><span data-stu-id="5c098-112">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="5c098-113">Navštivte prosím [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span><span class="sxs-lookup"><span data-stu-id="5c098-113">Please visit , [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span></span>

<span data-ttu-id="5c098-114">Poznámka: Pokud není k dispozici pro více uživatelů, kteří dříve měl přístup na OneDrive nebo SharePoint Server, může existovat problém dočasnou službu.</span><span class="sxs-lookup"><span data-stu-id="5c098-114">Note: If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="5c098-115">[Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="5c098-115">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


  


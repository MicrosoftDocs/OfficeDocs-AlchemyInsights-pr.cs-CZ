---
title: Vytvoření uživatele
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/11/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003231"
- "9403"
ms.openlocfilehash: 742ff857141d08031302fdcff7e49b3eef90e0f7
ms.sourcegitcommit: 186281d0b87d67f041c127d4334faa937da9a48a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743437"
---
# <a name="create-user"></a><span data-ttu-id="eeb6c-102">Vytvoření uživatele</span><span class="sxs-lookup"><span data-stu-id="eeb6c-102">Create user</span></span>

<span data-ttu-id="eeb6c-103">**OZNÁMENÍ:**</span><span class="sxs-lookup"><span data-stu-id="eeb6c-103">**ANNOUNCEMENT:**</span></span>

- <span data-ttu-id="eeb6c-104">[Od 4. ledna 2021 od Googlu se od 4. ledna 2021 odsoudí](https://docs.microsoft.com/azure/active-directory/external-identities/google-federation#deprecation-of-webview-sign-in-support) podpora pro přihlášení k WebView.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-104">[Deprecation of WebView sign-in support from Google starting January 4, 2021](https://docs.microsoft.com/azure/active-directory/external-identities/google-federation#deprecation-of-webview-sign-in-support) .</span></span> <span data-ttu-id="eeb6c-105">Otestujte, jestli vaše aplikace nemusí být ovlivněné pokyny [Společnosti Google pro](https://go.microsoft.com/fwlink/?linkid=2157323) testování kompatibility.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-105">Test whether your apps may be affected by following [Google’s guidance](https://go.microsoft.com/fwlink/?linkid=2157323) on testing compatibility.</span></span>
- <span data-ttu-id="eeb6c-106">Při přihlašování uživatelů pomocí spotřebitelských účtů Google se ujistěte, že používáte webové zobrazení systému nebo prohlížeč systému.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-106">Make sure you use the system webview or system browser when signing in your users with consumer Google accounts.</span></span> <span data-ttu-id="eeb6c-107">Další informace najdete v tématu Problémy s přihlášením k aplikacím jenom [v prohlížeči Chrome.](https://docs.microsoft.com/office365/troubleshoot/miscellaneous/chrome-behavior-affects-applications)</span><span class="sxs-lookup"><span data-stu-id="eeb6c-107">For more information, see [Issues signing in to application(s) using Chrome browser only](https://docs.microsoft.com/office365/troubleshoot/miscellaneous/chrome-behavior-affects-applications).</span></span>

<span data-ttu-id="eeb6c-108">**Nemůžu vytvořit nového uživatele v adresáři Azure AD**</span><span class="sxs-lookup"><span data-stu-id="eeb6c-108">**I can't create a new user in my Azure AD directory**</span></span>

1. <span data-ttu-id="eeb6c-109">Ujistěte se, že máte oprávnění k vytvoření nového standardního uživatele.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-109">Ensure that you are authorized to create a new standard user.</span></span> <span data-ttu-id="eeb6c-110">Nového standardního uživatele může vytvořit jenom role globálního správce nebo správce uživatelů v Azure Active Directory (AD).</span><span class="sxs-lookup"><span data-stu-id="eeb6c-110">Only the Global administrator or User administrator role in Azure Active Directory (AD) can create a new standard user.</span></span> <span data-ttu-id="eeb6c-111">Pokud nejste v jedné z těchto rolí, požádejte správce o přidání do jedné z těchto rolí nebo o vytvoření nového uživatelského účtu za vás.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-111">If you're not in one of these roles, ask an administrator to add you to one of these roles or to create the new user account for you.</span></span>
1. <span data-ttu-id="eeb6c-112">Ujistěte se, že je uživatelské jméno v doméně, která je ověřená ve vaší službě Azure AD.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-112">Ensure that the user name is in a domain that is verified in your Azure AD.</span></span> <span data-ttu-id="eeb6c-113">Pokud ve službě Azure AD nemáte žádné ověřené vlastní názvy domén, můžete použít počáteční doménu Azure AD, která končí \*.onmicrosoft.com.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-113">If you do not have any verified custom domain names in your Azure AD, you can use your Azure AD initial domain, which ends with \*.onmicrosoft.com.</span></span>
1. <span data-ttu-id="eeb6c-114">Ujistěte se, že je uživatelské jméno v doméně, která není federovaná do Azure AD z místní služby AD.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-114">Ensure that the user name is in a domain that is not federated to Azure AD from your on-premises AD.</span></span> <span data-ttu-id="eeb6c-115">Uživatele nelze přidat do cloudu s názvy domén, které jsou federované z místního prostředí.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-115">Users cannot be added in the cloud with domain names that are federated from on-premises.</span></span>
1. <span data-ttu-id="eeb6c-116">Ujistěte se, že žádný jiný uživatel ani kontakt už nemá uživatelské jméno, které chcete novému uživateli přiřadit.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-116">Ensure that no other user or contact already has the user name that you want to assign to the new user.</span></span> <span data-ttu-id="eeb6c-117">Uživatelská jména musí být jedinečná ve službě Azure AD.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-117">User names must be unique across Azure AD.</span></span>
1. <span data-ttu-id="eeb6c-118">Podívejte [se na role a správce Azure AD](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) pro azure AD.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-118">See [Azure AD roles and administrators](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) for your Azure AD.</span></span>
1. <span data-ttu-id="eeb6c-119">Podívejte se [na názvy](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) domén pro azure AD.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-119">See the [domain names](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) for your Azure AD.</span></span>
1. <span data-ttu-id="eeb6c-120">Prohlédněte [si protokoly](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) auditování a podívejte se na podrobnější informace o nedávno vytvořeném nebo odstraněných uživatelech, jako je kdo akci provedl a kdy.</span><span class="sxs-lookup"><span data-stu-id="eeb6c-120">Review [Audit logs](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/RolesAndAdministrators) to see more detailed information about a recently created or deleted user like who performed the action and when.</span></span>
1. <span data-ttu-id="eeb6c-121">Další informace o přidávání nových uživatelů najdete v tématu Použití portálu Azure Portal k vytvoření nového [uživatele ve službě Azure AD](/azure/active-directory/active-directory-users-create-azure-portal).</span><span class="sxs-lookup"><span data-stu-id="eeb6c-121">For more information on adding new users, see [Use the Azure portal to create a new user in your Azure AD](/azure/active-directory/active-directory-users-create-azure-portal).</span></span>
1. <span data-ttu-id="eeb6c-122">[Role správy Azure AD:](https://docs.microsoft.com/azure/active-directory/active-directory-assign-admin-roles)Oprávnění rolí správce v Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="eeb6c-122">[Azure AD administrative roles](https://docs.microsoft.com/azure/active-directory/active-directory-assign-admin-roles): Administrator role permissions in Azure Active Directory</span></span>
1. <span data-ttu-id="eeb6c-123">K vytvoření [nového uživatele můžete taky použít Azure AD PowerShell.](https://docs.microsoft.com/powershell/module/azuread/new-azureaduser?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="eeb6c-123">You can also [use Azure AD PowerShell to create a new user](https://docs.microsoft.com/powershell/module/azuread/new-azureaduser?view=azureadps-2.0).</span></span>
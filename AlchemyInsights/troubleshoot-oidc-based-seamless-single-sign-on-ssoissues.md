---
title: Řešení potíží s bezproblémovým jednotným přihlašováním (SSO) založeným na OIDC
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004357"
- "9375"
ms.openlocfilehash: e4ddde6176d9ab021b93e23b3cb363e10b1c1048
ms.sourcegitcommit: be246651064dfeacc866b2f69c0dbe4002a73f1c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2021
ms.locfileid: "50743453"
---
# <a name="troubleshoot-oidc-based-seamless-single-sign-on-sso-issues"></a><span data-ttu-id="7f296-102">Řešení potíží s bezproblémovým jednotným přihlašováním (SSO) založeným na OIDC</span><span class="sxs-lookup"><span data-stu-id="7f296-102">Troubleshoot OIDC-based Seamless Single Sign-on (SSO) issues</span></span>

- <span data-ttu-id="7f296-103">Informace o tom, jak přidat aplikaci založenou na OIDC do tenanta Azure, najdete v tématu Rychlý start: Nastavení jednotného přihlašování [(SSO)](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-setup-oidc-sso)založeného na OIDC pro aplikaci v tenantovi Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="7f296-103">To learn how to add an OIDC-based app to your Azure tenant, see [Quickstart: Set up OIDC-based single sign-on (SSO) for an application in your Azure Active Directory (Azure AD) tenant](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-setup-oidc-sso).</span></span>
- <span data-ttu-id="7f296-104">Další informace o aplikacích, které používají standard OpenID Connect k implementaci jednotného přihlašování, najdete v tématu Princip jednotného přihlašování založeného na [OIDC.](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-oidc-single-sign-on)</span><span class="sxs-lookup"><span data-stu-id="7f296-104">For more details about apps that use the OpenID Connect standard to implement single sign-on, see [Understand OIDC-based single sign-on](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-oidc-single-sign-on).</span></span>
- <span data-ttu-id="7f296-105">Informace pro případ, že se rozhodnete napsat kód přímo odesláním a zpracováním požadavků HTTP nebo použijete open-source knihovnu třetí strany, a ne pomocí jedné z našich open-source knihoven, najdete v článku [Protokoly OAuth 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-protocols)a OpenID Connect na platformě identit Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="7f296-105">For information in case you choose to write your code by directly sending and handling HTTP requests or use a third-party open-source library, rather than using one of our open-source libraries, see [OAuth 2.0 and OpenID Connect protocols on the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-protocols).</span></span>

<span data-ttu-id="7f296-106">**Protokoly**</span><span class="sxs-lookup"><span data-stu-id="7f296-106">**Protocols**</span></span>

1. <span data-ttu-id="7f296-107">[Platforma identit Microsoftu](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-implicit-grant-flow) a implicitní tok udělení – Určující charakteristikou implicitního grantu je, že tokeny (tokeny ID nebo přístupové tokeny) jsou vráceny přímo z koncového bodu /authorize místo koncového bodu /token.</span><span class="sxs-lookup"><span data-stu-id="7f296-107">[Microsoft identity platform and implicit grant flow](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-implicit-grant-flow) - The defining characteristic of the implicit grant is that tokens (ID tokens or access tokens) are returned directly from the /authorize endpoint instead of the /token endpoint.</span></span> <span data-ttu-id="7f296-108">Tento kód se často používá jako součást toku autorizačního kódu, který se nazývá **"hybridní tok" –** načtení tokenu ID v žádosti /authorize spolu s autorizačním kódem .</span><span class="sxs-lookup"><span data-stu-id="7f296-108">This is often used as part of the authorization code flow, in what is called the **"hybrid flow" - retrieving the ID token on the /authorize request along with an authorization code**.</span></span> <span data-ttu-id="7f296-109">Tento článek popisuje, jak naprogramovat přímo proti protokolu ve vaší aplikaci a požádat o tokeny z Azure AD.</span><span class="sxs-lookup"><span data-stu-id="7f296-109">This article describes how to program directly against the protocol in your application to request tokens from Azure AD.</span></span>
2. <span data-ttu-id="7f296-110">Platforma identit Microsoftu a tok autorizačního kódu [OAuth 2.0](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-auth-code-flow) – Udělení autorizačního kódu OAuth 2.0 se může použít v aplikacích nainstalovaných na zařízení k získání přístupu k chráněným prostředkům, jako jsou webová rozhraní API.</span><span class="sxs-lookup"><span data-stu-id="7f296-110">[Microsoft identity platform and OAuth 2.0 authorization code flow](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-auth-code-flow) - The OAuth 2.0 authorization code grant can be used in apps that are installed on a device to gain access to protected resources, such as web APIs.</span></span> <span data-ttu-id="7f296-111">Pomocí implementace OAuth 2.0 na platformě identit Microsoftu můžete přidat přihlášení a přístup k rozhraní API do mobilních a **desktopových aplikací.**</span><span class="sxs-lookup"><span data-stu-id="7f296-111">Using the Microsoft identity platform implementation of OAuth 2.0, you can **add sign in and API access to your mobile and desktop apps**.</span></span> <span data-ttu-id="7f296-112">Tento článek popisuje, jak programovat přímo proti protokolu v aplikaci pomocí libovolného jazyka.</span><span class="sxs-lookup"><span data-stu-id="7f296-112">This article describes how to program directly against the protocol in your application using any language.</span></span>
3. <span data-ttu-id="7f296-113">[Platforma identit Microsoftu](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc) a protokol OpenID Connect – Pokud používáte implementaci OpenID Connect platformy Microsoft identity, můžete do svých aplikací přidat přihlášení a přístup k rozhraní API.</span><span class="sxs-lookup"><span data-stu-id="7f296-113">[Microsoft identity platform and OpenID Connect protocol](https://docs.microsoft.com/azure/active-directory/develop/v2-protocols-oidc) - When you use the Microsoft identity platform's implementation of OpenID Connect, you can add sign-in and API access to your apps.</span></span> <span data-ttu-id="7f296-114">Tento článek popisuje, jak to udělat nezávisle na jazyce a popisuje, jak odesílat a přijímat zprávy HTTP bez **použití open-source** knihoven Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="7f296-114">This article shows how to do this independent of language and describes how to **send and receive HTTP messages without using any Microsoft open-source libraries**.</span></span>
4. <span data-ttu-id="7f296-115">Platforma identit Microsoftu a tok přihlašovacích údajů klienta [OAuth 2.0](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow) – Pro přístup k prostředkům hostovaným na webu pomocí identity aplikace můžete použít udělení klientských přihlašovacích údajů OAuth 2.0 zadané v dokumentu RFC 6749, někdy nazývaném dvounohý **OAuth.**</span><span class="sxs-lookup"><span data-stu-id="7f296-115">[Microsoft identity platform and the OAuth 2.0 client credentials flow](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow) - You can use the OAuth 2.0 client credentials grant specified in RFC 6749, sometimes called **two-legged OAuth**, to access web-hosted resources by using the identity of an application.</span></span> <span data-ttu-id="7f296-116">Tento typ grantu se běžně používá pro interakce mezi serverem, které musí běžet na pozadí bez okamžité interakce s uživatelem.</span><span class="sxs-lookup"><span data-stu-id="7f296-116">This type of grant is commonly used for server-to-server interactions that must run in the background, without immediate interaction with a user.</span></span> <span data-ttu-id="7f296-117">Tyto typy aplikací se často označují jako **démony** nebo **účty služeb**.</span><span class="sxs-lookup"><span data-stu-id="7f296-117">These types of applications are often referred to as **daemons** or **service accounts**.</span></span> <span data-ttu-id="7f296-118">Tento článek popisuje, jak programovat přímo proti protokolu v aplikaci.</span><span class="sxs-lookup"><span data-stu-id="7f296-118">This article describes how to program directly against the protocol in your application.</span></span>
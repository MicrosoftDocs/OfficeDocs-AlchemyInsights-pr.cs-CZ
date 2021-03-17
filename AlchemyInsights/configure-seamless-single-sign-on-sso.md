---
title: Konfigurace bezproblémového jednotného přihlašování (SSO)
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
- "9004344"
- "9384"
ms.openlocfilehash: 32790b23547de36cd2864e85ebae67f54ad91707
ms.sourcegitcommit: 309b9f3e6e2ff622f95bb860d337d2c05b7bbe54
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/15/2021
ms.locfileid: "50841419"
---
# <a name="configure-seamless-single-sign-on-sso"></a><span data-ttu-id="f853f-102">Konfigurace bezproblémového jednotného přihlašování (SSO)</span><span class="sxs-lookup"><span data-stu-id="f853f-102">Configure Seamless Single Sign-on (SSO)</span></span>

<span data-ttu-id="f853f-103">**Konfigurace aplikací**</span><span class="sxs-lookup"><span data-stu-id="f853f-103">**Configure Applications**</span></span>

1. <span data-ttu-id="f853f-104">Hodnoty byste měli získat od dodavatele aplikace.</span><span class="sxs-lookup"><span data-stu-id="f853f-104">You should get the values from the application vendor.</span></span> <span data-ttu-id="f853f-105">Hodnoty můžete zadat ručně nebo nahrát soubor metadat a extrahovat tak hodnotu polí.</span><span class="sxs-lookup"><span data-stu-id="f853f-105">You can manually enter the values or upload a metadata file to extract the value of the fields.</span></span>
2. <span data-ttu-id="f853f-106">Mnoho aplikací už je předkonfigurovaných pro práci s Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f853f-106">Many apps have already been pre-configured to work with Azure AD.</span></span> <span data-ttu-id="f853f-107">Tyto aplikace jsou uvedené v galerii aplikací, které můžete procházet, když přidáte aplikaci do tenanta Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f853f-107">These apps are listed in the gallery of apps that you can browse when you add an app to your Azure AD tenant.</span></span> <span data-ttu-id="f853f-108">Série [rychlých startů](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure) vás provede celým procesem.</span><span class="sxs-lookup"><span data-stu-id="f853f-108">The [quickstart series](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure) walks you through the process.</span></span>
3. <span data-ttu-id="f853f-109">Pokud chcete vytvořit aplikaci, která není galerie, můžete kliknout na **+ tlačítko** Vytvořit vlastní aplikaci a dát aplikaci název.</span><span class="sxs-lookup"><span data-stu-id="f853f-109">To create a non-gallery application, you can click on **+ Create your own Application** button and give a name to your Application.</span></span>
    - <span data-ttu-id="f853f-110">Ve výchozím nastavení  vybere možnost Integrovat jakoukoli jinou aplikaci, kterou v galerii nenajdete, což je správná možnost pro aplikace mimo galerii.</span><span class="sxs-lookup"><span data-stu-id="f853f-110">By default, it will select **Integrate any other application you don't find in the gallery** which is the correct option for Non-gallery applications.</span></span>
    - <span data-ttu-id="f853f-111">Jakmile po **uvedení** názvu aplikace na tlačítko Vytvořit, vytvoří se nová aplikace Enterprise bez galerie.</span><span class="sxs-lookup"><span data-stu-id="f853f-111">Once you hit **Create** after putting the name for the application, it will create a new Non-gallery Enterprise Application.</span></span>
    - <span data-ttu-id="f853f-112">Potom můžete přejít na **jednotné** přihlašování  v části Správa této aplikace a uvidíte různé techniky implementace této aplikace ve vašem prostředí.</span><span class="sxs-lookup"><span data-stu-id="f853f-112">Then, you may navigate to **Single Sign-on** under **Manage** of that application and you will be able to see different techniques for implementing it in your environment.</span></span>

<span data-ttu-id="f853f-113">**Konfigurace bezproblémového jednotného přihlašování pro konkrétní aplikaci**</span><span class="sxs-lookup"><span data-stu-id="f853f-113">**Configure Seamless SSO for a specific application**</span></span>

<span data-ttu-id="f853f-114">U aplikací v galerii najdete podrobné podrobné pokyny.</span><span class="sxs-lookup"><span data-stu-id="f853f-114">For the apps in the gallery you will find detailed, step-by-step, instructions.</span></span> <span data-ttu-id="f853f-115">Pokud chcete získat přístup k krokům, můžete procházet seznam všech kurzů konfigurace aplikací v kurzech pro konfiguraci aplikací [SaaS.](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)</span><span class="sxs-lookup"><span data-stu-id="f853f-115">To access the steps you can browse a list of all app configuration tutorials at [SaaS app configuration tutorials](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list).</span></span>

<span data-ttu-id="f853f-116">**Konfigurace jednotného přihlašování založeného na protokolu SAML**</span><span class="sxs-lookup"><span data-stu-id="f853f-116">**Configure SAML-based SSO**</span></span>

1. <span data-ttu-id="f853f-117">[Rychlý start: Nastavení jednotného přihlašování (SSO)](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-setup-sso)založeného na protokolu SAML pro aplikaci v tenantovi Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f853f-117">[Quickstart: Set up SAML-based single sign-on (SSO) for an application in your Azure Active Directory (Azure AD) tenant](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-setup-sso).</span></span>
2. <span data-ttu-id="f853f-118">Další informace o možnosti jednotného přihlašování založené na protokolu SAML najdete v tématu Principy jednotného přihlašování založeného na [samlu.](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-saml-single-sign-on)</span><span class="sxs-lookup"><span data-stu-id="f853f-118">To learn more about the SAML-based option for single sign-on, see [Understand SAML-based single sign-on](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-saml-single-sign-on).</span></span>
3. <span data-ttu-id="f853f-119">Další informace o žádostech o ověření SAML 2.0 a odpovědích, které Azure Active Directory (Azure AD) podporuje pro jednotné Sign-On přihlašování (SSO), najdete v článku o jednotném [Sign-On SAML](https://docs.microsoft.com/azure/active-directory/develop/single-sign-on-saml-protocol).</span><span class="sxs-lookup"><span data-stu-id="f853f-119">To learn about the SAML 2.0 authentication requests and responses that Azure Active Directory (Azure AD) supports for Single Sign-On (SSO), see [Single Sign-On SAML protocol](https://docs.microsoft.com/azure/active-directory/develop/single-sign-on-saml-protocol).</span></span>
4. <span data-ttu-id="f853f-120">Informace o tom, jak vytvořit a nakonfigurovat jednotné přihlašování založené na protokolu SAML pro vaši aplikaci v Azure Active Directory (Azure AD) pomocí rozhraní Microsoft Graph [API,](https://docs.microsoft.com/graph/application-saml-sso-configure-api)najdete v tématu Konfigurace jednotného přihlašování založeného na protokolu SAML pro vaši aplikaci pomocí rozhraní Microsoft Graph API .</span><span class="sxs-lookup"><span data-stu-id="f853f-120">To learn how to create and configure a SAML-based single sign-on (SSO) for your application in Azure Active Directory (Azure AD) using the Microsoft Graph API, see [Configure SAML-based single sign-on for your application using the Microsoft Graph API](https://docs.microsoft.com/graph/application-saml-sso-configure-api).</span></span>
5. <span data-ttu-id="f853f-121">Informace o tom, jak Azure AD používá protokol SAML, najdete v článku Jak platforma [identit Microsoftu používá protokol SAML](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span><span class="sxs-lookup"><span data-stu-id="f853f-121">To learn how Azure AD uses the SAML protocol, see [How the Microsoft identity platform uses the SAML protocol](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span></span>

<span data-ttu-id="f853f-122">**Konfigurace tokenů a deklarací identity**</span><span class="sxs-lookup"><span data-stu-id="f853f-122">**Configure Tokens and Claims**</span></span>

1. <span data-ttu-id="f853f-123">[Postupy: Přizpůsobení deklarací vydaných v tokenu SAML pro podnikové aplikace](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization)</span><span class="sxs-lookup"><span data-stu-id="f853f-123">[How to: customize claims issued in the SAML token for enterprise applications](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization).</span></span>
2. <span data-ttu-id="f853f-124">Informace o konfiguraci deklarací identity pomocí PowerShellu najdete v tématu Postup: Přizpůsobení deklarací identity vydávané v tokenech pro konkrétní aplikaci v [tenantovi (Preview).](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping)</span><span class="sxs-lookup"><span data-stu-id="f853f-124">To learn how to configure claims using PowerShell, see [How to: Customize claims emitted in tokens for a specific app in a tenant (Preview)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping).</span></span>
3. <span data-ttu-id="f853f-125">Informace o konfiguraci nepovinných deklarací identity najdete v tématu [Postup: Poskytnutí volitelných deklarací do aplikace](https://docs.microsoft.com/azure/active-directory/develop/active-directory-optional-claims).</span><span class="sxs-lookup"><span data-stu-id="f853f-125">To learn how to configure optional claims, see [How to: Provide optional claims to your app](https://docs.microsoft.com/azure/active-directory/develop/active-directory-optional-claims).</span></span>
4. <span data-ttu-id="f853f-126">Informace o tom, jak používat atributy rozšíření schématu adresáře pro posílání uživatelských dat do aplikací v deklaracích tokenů, najdete v tématu Použití atributů rozšíření [schématu adresáře v deklaracích identity](https://docs.microsoft.com/azure/active-directory/develop/active-directory-schema-extensions).</span><span class="sxs-lookup"><span data-stu-id="f853f-126">To learn how to use directory schema extension attributes for sending user data to applications in token claims, see [Using directory schema extension attributes in claims](https://docs.microsoft.com/azure/active-directory/develop/active-directory-schema-extensions).</span></span>
5. <span data-ttu-id="f853f-127">Informace o konfiguraci životnosti tokenů najdete v tématu Konfigurovatelné životnosti tokenů na platformě [identit Microsoftu (preview).](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes)</span><span class="sxs-lookup"><span data-stu-id="f853f-127">To learn how to configure token lifetimes, see [Configurable token lifetimes in the Microsoft identity platform (preview)](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).</span></span>
6. <span data-ttu-id="f853f-128">[Konfigurace zásad životnosti tokenů (preview)](https://docs.microsoft.com/azure/active-directory/develop/configure-token-lifetimes) – V tomto článku procházíme běžným scénářem zásad, který vám může pomoct zavést nová pravidla pro životnost tokenů.</span><span class="sxs-lookup"><span data-stu-id="f853f-128">[Configure token lifetime policies (preview)](https://docs.microsoft.com/azure/active-directory/develop/configure-token-lifetimes) - In this article, we walk through a common policy scenario that can help you impose new rules for token lifetime.</span></span> <span data-ttu-id="f853f-129">V příkladu se dozvíte, jak vytvořit zásadu, která vyžaduje, aby uživatelé ve webové aplikaci ověřovat častěji.</span><span class="sxs-lookup"><span data-stu-id="f853f-129">In the example, you learn how to create a policy that requires users to authenticate more frequently in your web app.</span></span>

<span data-ttu-id="f853f-130">**Poradce při potížích s konfigurací jednotného přihlašování**</span><span class="sxs-lookup"><span data-stu-id="f853f-130">**Troubleshoot SSO Configuration**</span></span>

- <span data-ttu-id="f853f-131">Časté otázky k Azure Active Directory Seamless Single Sign-On (Bezproblémové jednotné přihlašování) najdete v tématu [Azure Active Directory Seamless Single Sign-On: Frequently asked questions](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-faq).</span><span class="sxs-lookup"><span data-stu-id="f853f-131">For frequently asked questions about Azure Active Directory Seamless Single Sign-On (Seamless SSO), see [Azure Active Directory Seamless Single Sign-On: Frequently asked questions](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-faq).</span></span>
- <span data-ttu-id="f853f-132">Informace o běžných problémech týkajících se Azure Active Directory (Azure AD) Seamless Single Sign-On (Bezproblémové jednotné přihlašování) najdete v tématu Řešení potíží s bezproblémovým jednotným přihlašováním azure [active directory.](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso)</span><span class="sxs-lookup"><span data-stu-id="f853f-132">For troubleshooting information about common problems regarding Azure Active Directory (Azure AD) Seamless Single Sign-On (Seamless SSO), see [Troubleshoot Azure Active Directory Seamless Single Sign-On](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso).</span></span>
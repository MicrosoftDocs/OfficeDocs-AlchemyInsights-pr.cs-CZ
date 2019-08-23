---
title: S externím uživatelům sdílení nefunguje.
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36502224"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="7ae93-102">Řešení potíží s externím uživatelům sdílení obsahu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="7ae93-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="7ae93-103">Ujistěte se, že externí sdílení pro vaši organizaci:</span><span class="sxs-lookup"><span data-stu-id="7ae93-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="7ae93-104">Přejděte [služby &amp; stránku doplňky ve středisku pro správce služeb Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klepněte na tlačítko **servery**.</span><span class="sxs-lookup"><span data-stu-id="7ae93-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="7ae93-105">Zkontrolujte, zda že je zapnuto nastavení "On".</span><span class="sxs-lookup"><span data-stu-id="7ae93-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="7ae93-106">Pokud je vybrána "Pouze existující externí uživatelé", přesvědčte se, zda externí uživatel je uveden ve středisku pro správce služeb Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="7ae93-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="7ae93-107">Přesvědčte se, zda externí sdílení zapnuta pro web.</span><span class="sxs-lookup"><span data-stu-id="7ae93-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="7ae93-108">Kolekce klasických webů:</span><span class="sxs-lookup"><span data-stu-id="7ae93-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="7ae93-109">V centru nového správce služby SharePoint v levém podokně klepněte na tlačítko **servery**.</span><span class="sxs-lookup"><span data-stu-id="7ae93-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="7ae93-110">Vyberte web nebo weby a na pásu karet, klepněte na příkaz **sdílení**.</span><span class="sxs-lookup"><span data-stu-id="7ae93-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="7ae93-111">Pro týmový web, který patří do skupiny Office 365, nebo komunikační web:</span><span class="sxs-lookup"><span data-stu-id="7ae93-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="7ae93-112">Tyto nové typy webu Pokud budou mít stejné sdílení nastavení jako nastavení celoorganizačních celopodnikové nastavení umožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlásit.</span><span class="sxs-lookup"><span data-stu-id="7ae93-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="7ae93-113">V tomto případě weby povolit sdílení se nové a existující externí uživatelé přihlásit.</span><span class="sxs-lookup"><span data-stu-id="7ae93-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="7ae93-114">Chcete-li změnit nastavení pro konkrétní weby, použijte nové SharePoint admin center nebo PowerShell.</span><span class="sxs-lookup"><span data-stu-id="7ae93-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="7ae93-115">[Další informace](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="7ae93-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="7ae93-116">Externí sdílení nastavení libovolného webu může být více omezující než nastavení celoorganizačních ale povolující ne více než celopodnikové nastavení.</span><span class="sxs-lookup"><span data-stu-id="7ae93-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  


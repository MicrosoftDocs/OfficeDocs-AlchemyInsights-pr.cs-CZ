---
title: Poradce při potížích s chybu 404 Soubor nebyl nalezen.
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 1b15444c-367b-4523-8e08-1c77bbea7524
ms.openlocfilehash: 467feb3cb436a2e0135162657876e5c45d8d56bd
ms.sourcegitcommit: 03258ec4f5476a1ea6dd3a31d17bda815bc5a18a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/24/2019
ms.locfileid: "33243214"
---
# <a name="troubleshoot-error-404-file-not-found"></a><span data-ttu-id="e8c6c-102">Poradce při potížích s chybu 404 Soubor nebyl nalezen.</span><span class="sxs-lookup"><span data-stu-id="e8c6c-102">Troubleshoot Error 404, File not found</span></span>

<span data-ttu-id="e8c6c-103">404 chyba je přijat při uživatelé jsou pokusu o přístup k webu nebo souboru služby SharePoint nebo OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e8c6c-103">An Error 404 is received when users are attempting to access a site or file in SharePoint or OneDrive.</span></span> <span data-ttu-id="e8c6c-104">To je často způsobeno webu nebo souboru nebo skupiny získávání přejmenován, přesunut nebo odstraněn.</span><span class="sxs-lookup"><span data-stu-id="e8c6c-104">This is often caused by a site or file or group getting renamed, moved or deleted.</span></span> <span data-ttu-id="e8c6c-105">Například: uživatelé budou mít chybu 404, pokusu o přístup ke kořenové kolekci webů a byla odstraněna.</span><span class="sxs-lookup"><span data-stu-id="e8c6c-105">For example: Users will experience a 404 Error attempting to access the Root Site Collection and it has been deleted.</span></span>

<span data-ttu-id="e8c6c-106">Chcete-li vyřešit chybu 404 pro web, který byl přejmenován, přesunut nebo odstraněn:</span><span class="sxs-lookup"><span data-stu-id="e8c6c-106">To resolve Error 404 for a Site that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="e8c6c-107">Klasické servery, které existují v klasickém Admin Center viz [Obnovení odstraněných webů](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="e8c6c-107">For classic sites that exist in the Classic Admin Center, see [Restore a deleted site collection](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>


<span data-ttu-id="e8c6c-108">Moderní servery (komunikace, připojené skupiny nebo jiné weby) nacházející se v centru nového správce služby SharePoint viz [zobrazení a obnovení odstraněné stránky v nové Centrum správy služby SharePoint](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="e8c6c-108">For modern sites (communication, group-connected, or other sites) that exist in the new SharePoint admin center, see [View and restore deleted sites in the new SharePoint admin center](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>

<span data-ttu-id="e8c6c-109">Chcete-li vyřešit chybu 404 soubor (nebo jiné položky), která byla přejmenována, přesunuta nebo odstraněna:</span><span class="sxs-lookup"><span data-stu-id="e8c6c-109">To resolve Error 404 for a File (or other item) that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="e8c6c-110">Přejděte na web služby SharePoint nebo OneDrive a zobrazení koše z obsahu webu.</span><span class="sxs-lookup"><span data-stu-id="e8c6c-110">Go to the SharePoint or OneDrive site and view the Recycle Bin from the Site contents.</span></span> <span data-ttu-id="e8c6c-111">V části [obnovit položky do složky Koš webu služby SharePoint](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span><span class="sxs-lookup"><span data-stu-id="e8c6c-111">See, [Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span></span>

<span data-ttu-id="e8c6c-112">Pokud stále nelze najít položku Protokol auditu lze hledat v případě, že protokolování je povoleno zobrazíte, [hledání auditu přihlášení zabezpečení Office 365 & centra kompatibility](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span><span class="sxs-lookup"><span data-stu-id="e8c6c-112">If you are still unable to find the item you can search the audit log if logging is enabled see, [Search the audit log in the Office 365 Security & Compliance Center](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span></span>
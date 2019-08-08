---
title: Poradce při potížích s přístup odepřen zprávy OneDrive pro obchodní sítě
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d47ce80bdd07a25d9724057edf0289808a00a3db
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232513"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="53e8f-102">Poradce při potížích s přístup odepřen zprávy OneDrive pro obchodní sítě</span><span class="sxs-lookup"><span data-stu-id="53e8f-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="53e8f-103">Tento problém nastává nejčastěji v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN).</span><span class="sxs-lookup"><span data-stu-id="53e8f-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="53e8f-104">Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport).</span><span class="sxs-lookup"><span data-stu-id="53e8f-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="53e8f-105">Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID.</span><span class="sxs-lookup"><span data-stu-id="53e8f-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="53e8f-106">Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU).</span><span class="sxs-lookup"><span data-stu-id="53e8f-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="53e8f-107">Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.</span><span class="sxs-lookup"><span data-stu-id="53e8f-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="53e8f-108">Chcete-li vyřešit tento problém by mělo obnovit původní hlavní název uživatele pomocí kroků popsaných v následujícím článku[obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="53e8f-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>
2. <span data-ttu-id="53e8f-109">Pokud nemůžete obnovit původní uživatele byste měli odebrat staré uživatele z webu OneDrive pomocí těchto kroků [Odebrat uživatele ze seznamu informací o uživatelích]().</span><span class="sxs-lookup"><span data-stu-id="53e8f-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="53e8f-110">Po dokončení se můžete ověřit, zda že má uživatel práva správce k webu OneDrive pomocí následujícího postupu chcete-li [Přidat admin je pro uživatele OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="53e8f-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="53e8f-111">Další informace o úrovních oprávnění naleznete v článku [Principy úrovněmi oprávnění služby SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="53e8f-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>

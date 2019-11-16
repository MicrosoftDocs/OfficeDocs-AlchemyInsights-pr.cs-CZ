---
title: Odstraňování problémů s odepřeným přístupem k serverům OneDrive pro podnikové weby
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 3c40ad76a8961a3d0b4963483291c2a1364c51d3
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "37766704"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="42792-102">Odstraňování problémů s odepřeným přístupem k serverům OneDrive pro podnikové weby</span><span class="sxs-lookup"><span data-stu-id="42792-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="42792-103">K tomuto problému nejčastěji dochází, když je uživatel odstraněn a znovu vytvořen se stejným hlavním uživatelským jménem (UPN).</span><span class="sxs-lookup"><span data-stu-id="42792-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="42792-104">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="42792-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="42792-105">Když se uživatel pokusí o přístup k kolekci webů nebo k jejich objektu OneDrive, má uživatel nesprávný identifikátor PUID.</span><span class="sxs-lookup"><span data-stu-id="42792-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="42792-106">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory.</span><span class="sxs-lookup"><span data-stu-id="42792-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="42792-107">Pokud se uživatelé již přihlásili ke službě SharePoint a pak jsou přesunuté do jiné organizační jednotky a znovu synchronizovány se službou SharePoint, mohou k tomuto problému dojít.</span><span class="sxs-lookup"><span data-stu-id="42792-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="42792-108">Chcete-li tento problém vyřešit, obnovte původní název UPN podle kroků v článku, [obnovte uživatele v sadě Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="42792-108">To resolve this issue you should restore the original UPN with the steps in the article, [Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>
2. <span data-ttu-id="42792-109">Pokud původní uživatel nelze obnovit, měli byste odebrat původního uživatele z webu OneDrive pomocí těchto kroků, a [Odebrat uživatele ze seznamu informací o uživateli]().</span><span class="sxs-lookup"><span data-stu-id="42792-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="42792-110">Po provedení této funkce můžete ověřit, zda má uživatel oprávnění správce k webu OneDrive, a to podle kroků, které slouží k [Přidání správce na server OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive) .</span><span class="sxs-lookup"><span data-stu-id="42792-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="42792-111">Další informace o úrovních oprávnění naleznete v článku s [Principy úrovní oprávnění ve službě SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="42792-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>

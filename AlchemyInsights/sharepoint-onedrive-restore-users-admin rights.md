---
title: Udělit uživatelům přístup k webu služby SharePoint a OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759249"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="9c323-102">Udělit uživatelům přístup k webu služby SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="9c323-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="9c323-103">Tento problém nastává nejčastěji v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN).</span><span class="sxs-lookup"><span data-stu-id="9c323-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="9c323-104">Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport).</span><span class="sxs-lookup"><span data-stu-id="9c323-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="9c323-105">Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID.</span><span class="sxs-lookup"><span data-stu-id="9c323-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="9c323-106">Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU).</span><span class="sxs-lookup"><span data-stu-id="9c323-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="9c323-107">Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.</span><span class="sxs-lookup"><span data-stu-id="9c323-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="9c323-108">Chcete-li vyřešit tento problém by mělo obnovit původní hlavní název uživatele pomocí kroků popsaných v následujícím článku[obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="9c323-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="9c323-109">Po dokončení se můžete ověřit, zda že má uživatel práva správce k webu OneDrive pomocí následujícího postupu chcete-li [Přidat admin je pro uživatele OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="9c323-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="9c323-110">Další informace o úrovních oprávnění naleznete v článku [Principy úrovněmi oprávnění služby SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="9c323-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>

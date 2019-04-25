---
title: Oprávnění problémy při migraci
ms.author: kirks
author: Techwriter40
ms.date: 9/18/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: cbec51a7-5513-4848-a9ae-cdf993e000a8
ms.openlocfilehash: 3cdf5909595b5b1fac9aeb00865546c1dcff5f09
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32372157"
---
# <a name="user-profile-and-photo-synchronization"></a><span data-ttu-id="e9469-102">Synchronizace uživatelského profilu a fotografií</span><span class="sxs-lookup"><span data-stu-id="e9469-102">User Profile and Photo synchronization</span></span>

 <span data-ttu-id="e9469-103">**Synchronizace profilu fotografii** - uživatelé všimnout, že jejich profilu fotografii není synchronizace služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e9469-103">**Profile Photo Synchronization** - Users may notice that their profile photo is not synchronizing to SharePoint.</span></span> <span data-ttu-id="e9469-104">Nebo se může jste se pokusili aktualizovat jejich profil fotografie a fotografie se stále zobrazuje jako staré fotografie.</span><span class="sxs-lookup"><span data-stu-id="e9469-104">Or, they may have tried to update their profile photo and the photo still appears as the old photo.</span></span> <span data-ttu-id="e9469-105">Zajistit, že fotografie profilu se zobrazí podle očekávání uživatele bude nutné zahájit synchronizaci fotografií.</span><span class="sxs-lookup"><span data-stu-id="e9469-105">To ensure the profile photo shows as expected, the user will need to initiate a photo sync.</span></span> 
  
<span data-ttu-id="e9469-106">Další informace o procesu synchronizace fotografií naleznete v tématu [informace o profilu synchronizace obrázků ve službách Office 365](https://go.microsoft.com/fwlink/?linkid=2022634)</span><span class="sxs-lookup"><span data-stu-id="e9469-106">For more information about the photo synchronization process, see [Information about profile picture synchronization in Office 365](https://go.microsoft.com/fwlink/?linkid=2022634)</span></span>
  
- <span data-ttu-id="e9469-107">**Synchronizace profilu** - čas, který má potřebné k dokončení synchronizace profilu závisí na počtu změn (práce) má úlohu importu AD procesu.</span><span class="sxs-lookup"><span data-stu-id="e9469-107">**Profile Synchronization** - The time that's required to complete a profile synchronization depends on the number of changes (work) the AD Import Job has to process.</span></span> <span data-ttu-id="e9469-108">Pokud existuje mnoho změn, úloha časovače má mnoho činnost a bude trvat déle, změny se projeví v aplikaci profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="e9469-108">If there are many changes, the timer job has a lot of work to do, and it will take longer for the changes to be reflected in the User Profile Application.</span></span> <span data-ttu-id="e9469-109">Pokud úloha časovače má malý objem práce do, změny se projeví v aplikaci profilů uživatelů, která je mnohem rychlejší.</span><span class="sxs-lookup"><span data-stu-id="e9469-109">If the timer job has a small volume of work to do, the changes will be reflected in the User Profile Application much faster.</span></span> 
  
<span data-ttu-id="e9469-110">Další informace o procesu synchronizace profilu naleznete v tématu [informace o synchronizace profilů uživatelů v Online služby SharePoint](https://go.microsoft.com/fwlink/?linkid=2022639)</span><span class="sxs-lookup"><span data-stu-id="e9469-110">For more information about the profile synchronization process, see [Information about user profile synchronization in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2022639)</span></span>
    
- <span data-ttu-id="e9469-111">**Aktualizace profilu v Office pustíte** - Delve uživatelé mohou spravovat svůj profil Office 365.</span><span class="sxs-lookup"><span data-stu-id="e9469-111">**Update Profile in Office Delve** - Delve users can manage their Office 365 Profile.</span></span> <span data-ttu-id="e9469-112">Další informace naleznete v tématu [zobrazení a aktualizaci profilu v Office pustíte](https://support.office.com/article/View-and-update-your-profile-in-Office-Delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span><span class="sxs-lookup"><span data-stu-id="e9469-112">For more information, see [View and Update your profile in Office Delve](https://support.office.com/article/View-and-update-your-profile-in-Office-Delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span></span>
    


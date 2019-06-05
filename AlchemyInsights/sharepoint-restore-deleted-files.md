---
title: Obnovení odstraněného souboru nebo složky
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ba1573a5-9f44-482b-8082-6f648f169449
ms.openlocfilehash: d5250d75a982c0afc9d3e1b2a43be2ba9c3e8f59
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716500"
---
## <a name="restore-a-deleted-file-or-folder"></a><span data-ttu-id="f7a18-102">Obnovení odstraněného souboru nebo složky</span><span class="sxs-lookup"><span data-stu-id="f7a18-102">Restore a deleted file or folder</span></span>

<span data-ttu-id="f7a18-103">SharePoint Online zálohování veškerého obsahu zachová 14 dnů další za skutečné odstranění.</span><span class="sxs-lookup"><span data-stu-id="f7a18-103">SharePoint Online retains backups of all content for 14 additional days beyond actual deletion.</span></span> <span data-ttu-id="f7a18-104">Pokud obsah nelze obnovit prostřednictvím Koš nebo obnovit soubory, můžete kontaktovat správce Microsoft Support požádat o obnovení kdykoli uvnitř okna 14 den.</span><span class="sxs-lookup"><span data-stu-id="f7a18-104">If content cannot be restored via the Recycle Bin or Files Restore, an administrator can contact Microsoft Support to request a restore any time inside the 14 day window.</span></span> <span data-ttu-id="f7a18-105">Obnovení ze zálohy lze provést pouze pro kolekce webů a podřízených webů, ne pro konkrétní soubory, seznamy nebo knihovny.</span><span class="sxs-lookup"><span data-stu-id="f7a18-105">Restorations from backups can only be completed for site collections or sub-sites, not for specific files, lists, or libraries.</span></span>

<span data-ttu-id="f7a18-106">Při odstranění položky nebo webu služby Sharepoint, není okamžitě odstraněna.</span><span class="sxs-lookup"><span data-stu-id="f7a18-106">When you delete an item or site from Sharepoint, it isn't immediately removed.</span></span> <span data-ttu-id="f7a18-107">Odstraněné položky Přejít do koše pro časové období.</span><span class="sxs-lookup"><span data-stu-id="f7a18-107">Deleted items go into the recycle bin for a period of time.</span></span> <span data-ttu-id="f7a18-108">Během této doby můžete obnovit odstraněné položky do původního umístění.</span><span class="sxs-lookup"><span data-stu-id="f7a18-108">During that time, you can restore the items you deleted to their original location.</span></span> <span data-ttu-id="f7a18-109">Další informace naleznete na níže uvedené odkazy.</span><span class="sxs-lookup"><span data-stu-id="f7a18-109">For more information, please visit the links below.</span></span>

<span data-ttu-id="f7a18-110">[Obnovení položky do složky Koš webu služby SharePoint](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="f7a18-110">[Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

[<span data-ttu-id="f7a18-111">Obnovit odstraněné soubory nebo složky v OneDrive</span><span class="sxs-lookup"><span data-stu-id="f7a18-111">Restore deleted files or folders in OneDrive</span></span>](https://support.office.com/en-us/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)

[<span data-ttu-id="f7a18-112">Obnovení odstraněných webů (včetně skupiny, komunikace a jiné servery)</span><span class="sxs-lookup"><span data-stu-id="f7a18-112">Restore a deleted site collection (Including group, communication and other sites)</span></span>](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)

[<span data-ttu-id="f7a18-113">Obnovení odstraněné webu OneDrive</span><span class="sxs-lookup"><span data-stu-id="f7a18-113">Restore a deleted OneDrive site</span></span>](https://docs.microsoft.com/en-us/onedrive/restore-deleted-onedrive)

<span data-ttu-id="f7a18-114">Pro hromadné recycle bin akce považovat admins pomocí [Služby Sharepoint Online PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span><span class="sxs-lookup"><span data-stu-id="f7a18-114">For bulk recycle bin actions, admins may consider using [Sharepoint Online PNP](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span></span>

## <a name="files-restore-feature"></a><span data-ttu-id="f7a18-115">Funkce obnovení souborů</span><span class="sxs-lookup"><span data-stu-id="f7a18-115">Files Restore feature</span></span>

<span data-ttu-id="f7a18-116">Pokud mnoho souborů OneDrive nebo Sharepoint získat odstraněny, přepsány, poškození nebo nakažen malwarem, předchozí čas pomocí funkce obnovení souborů můžete obnovit celou knihovnu OneDrive nebo služby Sharepoint.</span><span class="sxs-lookup"><span data-stu-id="f7a18-116">If lots of your OneDrive or Sharepoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or Sharepoint library to a previous time using the files restore feature.</span></span>

[<span data-ttu-id="f7a18-117">Obnovení knihovny OneDrive</span><span class="sxs-lookup"><span data-stu-id="f7a18-117">Restore a OneDrive library</span></span>](https://support.office.com/en-us/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

[<span data-ttu-id="f7a18-118">Obnovení knihovny dokumentů</span><span class="sxs-lookup"><span data-stu-id="f7a18-118">Restore a Document library</span></span>](https://support.office.com/en-us/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a?ui=en-US&amp;rs=en-US&amp;ad=US.)


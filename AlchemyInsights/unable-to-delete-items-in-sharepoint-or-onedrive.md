---
title: Nelze odstranit položky služby SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057688"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="6ee44-102">Nelze odstranit položky</span><span class="sxs-lookup"><span data-stu-id="6ee44-102">Unable to delete items</span></span>

<span data-ttu-id="6ee44-103">S odstraněním problémů?</span><span class="sxs-lookup"><span data-stu-id="6ee44-103">Having issues deleting items?</span></span>

- <span data-ttu-id="6ee44-104">Vždy zkontrolujte, zda že máte [příslušná oprávnění](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) k odstranění položky nebo mít požadavek na [správce kolekce webů](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) položku odebrat.</span><span class="sxs-lookup"><span data-stu-id="6ee44-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="6ee44-105">Ujistěte se, že není nastavení [zásad pro uchovávání informací](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) o položce.</span><span class="sxs-lookup"><span data-stu-id="6ee44-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="6ee44-106">Zkontrolujte, zda že položka není [rezervován](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) jiným uživatelem.</span><span class="sxs-lookup"><span data-stu-id="6ee44-106">Ensure the item is not [checked out](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="6ee44-107">Nakonec mohou správci [služby SharePoint vzory a postupy](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) obsahující knihovnu PowerShell příkazy, které umožňují provádět akce komplexní správy Vynutit odstranění stubborn položek.</span><span class="sxs-lookup"><span data-stu-id="6ee44-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span> 
- [<span data-ttu-id="6ee44-108">Odebrání PNP souboru</span><span class="sxs-lookup"><span data-stu-id="6ee44-108">Remove PNP File</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="6ee44-109">Odebrat složku PNP</span><span class="sxs-lookup"><span data-stu-id="6ee44-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="6ee44-110">Odebrat položku seznamu PNP</span><span class="sxs-lookup"><span data-stu-id="6ee44-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="6ee44-111">Odebrání seznamu PNP</span><span class="sxs-lookup"><span data-stu-id="6ee44-111">Remove PNP List</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="6ee44-112">Odebrání PNP pole (sloupec)</span><span class="sxs-lookup"><span data-stu-id="6ee44-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
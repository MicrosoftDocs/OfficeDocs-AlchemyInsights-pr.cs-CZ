---
title: Nastavit nebo změnit oprávnění veřejné složky
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: d1554e8a63455f3549044e526183c0e8709f2631
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30767277"
---
# <a name="permissions-and-public-folders"></a><span data-ttu-id="7cf66-102">Oprávnění a veřejné složky</span><span class="sxs-lookup"><span data-stu-id="7cf66-102">Permissions and Public Folders</span></span>

<span data-ttu-id="7cf66-103">Můžete změnit oprávnění na veřejné složky pomocí aplikace Outlook, středisku pro správce serveru Exchange (EAC) nebo PowerShell:</span><span class="sxs-lookup"><span data-stu-id="7cf66-103">You can change the permissions on your Public Folders using Outlook, the Exchange admin center (EAC), or PowerShell:</span></span>
  
- <span data-ttu-id="7cf66-104">Pro pokyny k aplikaci Outlook, [klepněte sem](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).</span><span class="sxs-lookup"><span data-stu-id="7cf66-104">For Outlook instructions, [click here](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).</span></span>
    
- <span data-ttu-id="7cf66-105">EAC naleznete v [tomto článku](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) pokyny.</span><span class="sxs-lookup"><span data-stu-id="7cf66-105">For EAC, refer to [this article](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) for instructions.</span></span> <span data-ttu-id="7cf66-106">Klepnutím [sem](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) přejdete do EAC.</span><span class="sxs-lookup"><span data-stu-id="7cf66-106">You can click [here](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) to navigate to EAC.</span></span> 
    
- <span data-ttu-id="7cf66-107">Prostředí Powershell naleznete v [tomto článku](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) pokyny k použití PowerShell přidat PublicFolderClientPermission..</span><span class="sxs-lookup"><span data-stu-id="7cf66-107">For Powershell, refer to [this article](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) for instructions on using the Add-PublicFolderClientPermission commandlet.</span></span> <span data-ttu-id="7cf66-108">Pokud potřebujete pokyny k připojení k serveru Exchange Powershell, klepněte [sem](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).</span><span class="sxs-lookup"><span data-stu-id="7cf66-108">If you need instructions to connect to Exchange Powershell, click [here](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).</span></span>
    
<span data-ttu-id="7cf66-109">Pokud **externí uživatelé nemohou odesílat e-mailové zprávy do veřejné složky pošty povolena**, důvodem může být že veřejné složky chybí oprávnění požadované pro doručení externí e-mailové.</span><span class="sxs-lookup"><span data-stu-id="7cf66-109">If **external users can't send emails to a mail-enabled Public Folder**, the reason might be that the public folder is missing permissions required for external email delivery.</span></span> <span data-ttu-id="7cf66-110">Problém můžete vyřešit pomocí pokynů aplikace Outlook [zde](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)nebo PowerShell pokyny [zde](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).</span><span class="sxs-lookup"><span data-stu-id="7cf66-110">You can fix this using the Outlook instructions [here](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1), or the PowerShell instructions [here](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).</span></span>
  


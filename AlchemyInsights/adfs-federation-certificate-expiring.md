---
title: Službou AD FS Federation vypršení platnosti certifikátu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 518261787b1b0df99ee7b3dc3e51dec70e4373bc
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30755147"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="15ae9-102">Službou AD FS Federation vypršení platnosti certifikátu</span><span class="sxs-lookup"><span data-stu-id="15ae9-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="15ae9-103">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="15ae9-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="15ae9-104">Nainstalujte Microsoft Azure Active Directory modul pro prostředí Windows PowerShell v počítači (Pokud již není nainstalován modul).</span><span class="sxs-lookup"><span data-stu-id="15ae9-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="15ae9-105">Chcete-li to provést, přejděte na příkaz [Spravovat Azure AD pomocí prostředí Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="15ae9-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>
    
2. <span data-ttu-id="15ae9-106">Postupujte podle pokynů "scénář 1: AD FS token podpisu certifikátu vypršela" části ["Došlo k chybě při přístupu na web" Chyba ze služby AD FS při federované uživatele služeb Office 365, Azure, nebo Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="15ae9-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
3. <span data-ttu-id="15ae9-107">Postupujte podle kroků v [tom, jak aktualizovat nebo opravit nastavení federované domény do služeb Office 365, Azure nebo Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="15ae9-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
    <span data-ttu-id="15ae9-108">Další informace o obnovování certifikátů federace, naleznete v tématu [obnovení certifikátů federace služeb Office 365 a Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="15ae9-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
    


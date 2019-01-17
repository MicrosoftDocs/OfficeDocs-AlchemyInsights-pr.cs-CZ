---
title: Řešení problémů s zápis Windows zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8d19bbd5a5782c7793c87499baf62b2eb7de82ae
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281902"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="285ff-102">Řešení problémů s zápis Windows zařízení v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="285ff-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="285ff-103">Zobrazit zdroje uvedené níže nyní vyřešit váš problém.</span><span class="sxs-lookup"><span data-stu-id="285ff-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="285ff-104">Některé běžné chybové zprávy a postup řešení:</span><span class="sxs-lookup"><span data-stu-id="285ff-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="285ff-p101">**Nelze nainstalovat software, 0x80cf4017:** Váš certifikát účtu vypršela. Znovu stáhněte balíček klientského počítače v konzole pro správu Intune. Další informace v této dokumentaci.</span><span class="sxs-lookup"><span data-stu-id="285ff-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="285ff-108">**Kód chyby 0x801c0003:** Došlo k chybě může dojít v následujících situacích:</span><span class="sxs-lookup"><span data-stu-id="285ff-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="285ff-p102">Uživatel má více zařízení, než je limit zařízení zapsán. Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/en-us/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="285ff-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="285ff-p103">"Uživatelé mohou připojit zařízení k Azure AD" je nastavena na "none". Nastaven na hodnotu vše nebo vyberte uživatele. Zkontrolujte [tuto dokumentaci](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) Další informace.</span><span class="sxs-lookup"><span data-stu-id="285ff-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="285ff-p104">Zařízení je již zapsán jiným uživatelem. Pokud tomu tak je, odebrání zařízení z konzoly Azure Intune nebo ručně unenroll zařízení před dalším pokusem.</span><span class="sxs-lookup"><span data-stu-id="285ff-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="285ff-p105">Zařízení se systém Windows 10 Home. Azure Active Directory se může účastnit pouze Pro systém Windows 10, vzdělávání a Enterprise SKU.</span><span class="sxs-lookup"><span data-stu-id="285ff-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="285ff-118">Další zdroje pomoci vyřešit váš problém:</span><span class="sxs-lookup"><span data-stu-id="285ff-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="285ff-p106">Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu. Přečtěte [dokument](https://docs.microsoft.com/en-us/intune/help-desk-operators) pro další podrobnosti.</span><span class="sxs-lookup"><span data-stu-id="285ff-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="285ff-121">Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="285ff-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="285ff-122">[Zjistěte, jak zapsat Windows zařízení v Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="285ff-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span></span>
  

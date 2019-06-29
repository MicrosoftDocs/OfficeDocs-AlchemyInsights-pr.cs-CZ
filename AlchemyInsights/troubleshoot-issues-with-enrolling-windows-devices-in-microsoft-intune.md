---
title: Řešení problémů s zápis Windows zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: fa48b76fb49cdeef0734e77520c9bf95c150f317
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353530"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="be487-102">Řešení problémů s zápis Windows zařízení v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="be487-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="be487-103">Zobrazit zdroje uvedené níže nyní vyřešit váš problém.</span><span class="sxs-lookup"><span data-stu-id="be487-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="be487-104">Některé běžné chybové zprávy a postup řešení:</span><span class="sxs-lookup"><span data-stu-id="be487-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="be487-105">**Nelze nainstalovat software, 0x80cf4017:** Váš certifikát účtu vypršela.</span><span class="sxs-lookup"><span data-stu-id="be487-105">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired.</span></span> <span data-ttu-id="be487-106">Znovu stáhněte balíček klientského počítače v konzole pro správu Intune.</span><span class="sxs-lookup"><span data-stu-id="be487-106">Re-download the PC Client software package in the Intune Admin Console.</span></span> <span data-ttu-id="be487-107">Další informace v této dokumentaci.</span><span class="sxs-lookup"><span data-stu-id="be487-107">Review this documentation for more information.</span></span>
  
 <span data-ttu-id="be487-108">**Kód chyby 0x801c0003:** Došlo k chybě může dojít v následujících situacích:</span><span class="sxs-lookup"><span data-stu-id="be487-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span>
  
1. <span data-ttu-id="be487-109">Uživatel má více zařízení, než je limit zařízení zapsán.</span><span class="sxs-lookup"><span data-stu-id="be487-109">The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="be487-110">Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="be487-110">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>

2. <span data-ttu-id="be487-111">"Uživatelé mohou připojit zařízení k Azure AD" je nastavena na "none".</span><span class="sxs-lookup"><span data-stu-id="be487-111">"Users may join devices to Azure AD" is set to "none".</span></span> <span data-ttu-id="be487-112">Nastaven na hodnotu vše nebo vyberte uživatele.</span><span class="sxs-lookup"><span data-stu-id="be487-112">Set it to all or select users.</span></span> <span data-ttu-id="be487-113">Zkontrolujte [tuto dokumentaci](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) Další informace.</span><span class="sxs-lookup"><span data-stu-id="be487-113">Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span>

3. <span data-ttu-id="be487-114">Zařízení je již zapsán jiným uživatelem.</span><span class="sxs-lookup"><span data-stu-id="be487-114">The device is already enrolled by another user.</span></span> <span data-ttu-id="be487-115">Pokud tomu tak je, odebrání zařízení z konzoly Azure Intune nebo ručně unenroll zařízení před dalším pokusem.</span><span class="sxs-lookup"><span data-stu-id="be487-115">If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>

4. <span data-ttu-id="be487-116">Zařízení se systém Windows 10 Home.</span><span class="sxs-lookup"><span data-stu-id="be487-116">The device is Windows 10 Home.</span></span> <span data-ttu-id="be487-117">Azure Active Directory se může účastnit pouze Pro systém Windows 10, vzdělávání a Enterprise SKU.</span><span class="sxs-lookup"><span data-stu-id="be487-117">Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>

<span data-ttu-id="be487-118">Další zdroje pomoci vyřešit váš problém:</span><span class="sxs-lookup"><span data-stu-id="be487-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="be487-119">Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu.</span><span class="sxs-lookup"><span data-stu-id="be487-119">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="be487-120">Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti.</span><span class="sxs-lookup"><span data-stu-id="be487-120">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="be487-121">Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="be487-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>

<span data-ttu-id="be487-122">[Zjistěte, jak zapsat Windows zařízení v Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="be487-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>

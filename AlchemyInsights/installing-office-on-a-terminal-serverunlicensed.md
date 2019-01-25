---
title: Instalace sady office na terminálovém serveru - bez licence
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 73d5128b55cae7712c48be9e2d05e558c3ba2e5c
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29463021"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="0c9b0-102">Instalace sady Office na terminálovém serveru</span><span class="sxs-lookup"><span data-stu-id="0c9b0-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="0c9b0-103">Pro nasazení sady Office 365 ProPlus na serveru systému Windows pomocí služby Remote Desktop Services (RDS), dříve se jmenovala Terminálové služby:</span><span class="sxs-lookup"><span data-stu-id="0c9b0-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="0c9b0-p101">Musí mít plán služeb Office 365, obsahující Office 365 ProPlus, například Office 365 Enterprise E3 nebo Enterprise E5. Plány Office 365 Business a Office 365 Business Premium neobsahují Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="0c9b0-p101">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5. The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
    
- <span data-ttu-id="0c9b0-106">Je nutné povolit [aktivací sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="0c9b0-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>
    
<span data-ttu-id="0c9b0-107">Pokud chcete nainstalovat sadu Office 365 ProPlus RDS z portálu služeb Office 365 \*\* *který používá výchozí nastavení instalace* \*\*, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="0c9b0-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span> 
  
1. <span data-ttu-id="0c9b0-p102">Zkontrolujte, jaký plán služeb Office 365 máte. [Informace jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span><span class="sxs-lookup"><span data-stu-id="0c9b0-p102">Check what Office 365 plan you have. [Learn how](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span></span>
    
2. <span data-ttu-id="0c9b0-p103">Pokud je plán nutné přepnout do různých služeb Office 365. [Informace jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span><span class="sxs-lookup"><span data-stu-id="0c9b0-p103">If necessary, switch to a different Office 365 plan. [Learn how](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span></span>
    
3. <span data-ttu-id="0c9b0-p104">Již je nainstalována sada Office na serveru RDS pomocí jiné plány služeb Office 365, odinstalujte jej. Například v Ovládacích panelech \> odinstalovat program. Odinstalujte, pokud používáte do problémy pomocí [odborné pomoci společnosti Microsoft a Pomocník pro obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) .</span><span class="sxs-lookup"><span data-stu-id="0c9b0-p104">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it. For example, by going to Control Panel \> Uninstall a program. Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span> 
    
4. <span data-ttu-id="0c9b0-115">Na serveru RDS Přihlaste se k portálu služeb Office 365 pomocí účtu správce a [instalaci sady Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="0c9b0-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
    
5. <span data-ttu-id="0c9b0-116">Po instalaci sady Office \*\* *bez otevření nebo přihlášení* \*\* na všechny aplikace sady Office.</span><span class="sxs-lookup"><span data-stu-id="0c9b0-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span> 
    
6. <span data-ttu-id="0c9b0-117">Na serveru RDS povolte aktivací sdíleného počítače pomocí úpravy registru pomocí následujících kroků:</span><span class="sxs-lookup"><span data-stu-id="0c9b0-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
    
1. <span data-ttu-id="0c9b0-p105">Klepněte pravým tlačítkem myši tlačítko v levém dolním rohu obrazovky a vyberte příkaz spustit. Do pole Otevřít zadejte **příkaz regedit**a potom klepněte na tlačítko OK.</span><span class="sxs-lookup"><span data-stu-id="0c9b0-p105">Right-click the Windows button in the lower left-hand corner of your screen and select Run. In the Open box, type **regedit**, and then select OK.</span></span> 
    
2. <span data-ttu-id="0c9b0-120">Klepněte na tlačítko Ano po zobrazení výzvy povolte editoru registru provádět změny zařízení.</span><span class="sxs-lookup"><span data-stu-id="0c9b0-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>
    
3. <span data-ttu-id="0c9b0-121">V editoru registru přidejte řetězcovou hodnotu z **SharedComputerLicensing** na hodnotu 1 v části HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="0c9b0-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span> 
    
7. <span data-ttu-id="0c9b0-122">Na serveru RDS \*\* *Přihlásit jako koncový uživatel* \*\* a [Ověřte, zda je povoleno sdílené počítače aktivace pro Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="0c9b0-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
    
<span data-ttu-id="0c9b0-123">Další informace o požadavky, pokyny k instalaci a návod pro nástroj pro nasazení sady Office pomocí vlastní instalace naleznete v tématu [Nasazení sady Office 365 ProPlus pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="0c9b0-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="0c9b0-124">Chcete-li opravit chyby související s aktivací sdíleného počítače, naleznete [Poradce při potížích s problémy s aktivací sdíleného počítače pro Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="0c9b0-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  


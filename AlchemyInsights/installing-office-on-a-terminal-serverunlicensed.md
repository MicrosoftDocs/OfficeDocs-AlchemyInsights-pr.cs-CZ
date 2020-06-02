---
title: Instalace kanceláře na terminálový server – bez licence
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: c781e9fd492ff97bc80667956e6609b3d40b28b4
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508621"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="1ad2a-102">Instalace Office na terminálový server</span><span class="sxs-lookup"><span data-stu-id="1ad2a-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="1ad2a-103">Pro nasazení aplikací Microsoft 365 pro podniky na systému Windows Server pomocí služby Vzdálená plocha (RDS), dříve pojmenované Terminálové služby:</span><span class="sxs-lookup"><span data-stu-id="1ad2a-103">For deploying Microsoft 365 Apps for enterprise on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="1ad2a-104">Musíte mít předplatné Microsoft 365, které zahrnuje aplikace Microsoft 365 Pro podniky, jako je Office 365 Enterprise E3 nebo Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-104">You must have a Microsoft 365 subscription that includes Microsoft 365 Apps for enterprise, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="1ad2a-105">Microsoft 365 Apps pro firmy a Microsoft 365 Apps pro firmy Premium plány neobsahují Microsoft 365 Apps pro podniky.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-105">The Microsoft 365 Apps for business and Microsoft 365 Apps for business Premium plans do not include Microsoft 365 Apps for enterprise.</span></span>

- <span data-ttu-id="1ad2a-106">Je třeba povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="1ad2a-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span></span>

<span data-ttu-id="1ad2a-107">Pokud chcete nainstalovat Microsoft 365 Apps pro podniky na RDS z Centra pro správu Microsoft 365, ***které používá výchozí nastavení instalace***, postupujte podle následujících kroků.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-107">If you want to install Microsoft 365 Apps for enterprise on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="1ad2a-108">Můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) a nainstalovat aplikace Microsoft 365 Apps pro podniky v režimu aktivace sdíleného počítače.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Microsoft 365 Apps for enterprise in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="1ad2a-109">Podívejte se, jaké předplatné Microsoft 365 máte.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-109">Check what Microsoft 365 subscription you have.</span></span> [<span data-ttu-id="1ad2a-110">Přečtěte si, jak</span><span class="sxs-lookup"><span data-stu-id="1ad2a-110">Learn how</span></span>](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="1ad2a-111">V případě potřeby přepněte na jiné předplatné Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-111">If necessary, switch to a different Microsoft 365 subscription.</span></span> [<span data-ttu-id="1ad2a-112">Přečtěte si, jak</span><span class="sxs-lookup"><span data-stu-id="1ad2a-112">Learn how</span></span>](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan)

3. <span data-ttu-id="1ad2a-113">Pokud už je Office nainstalovaný na serveru RDS s jinými předplatnými Microsoftu 365, odinstalujte ho.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-113">If Office is already installed on the RDS server using any other Microsoft 365 subscriptions, uninstall it.</span></span> <span data-ttu-id="1ad2a-114">Například tím, že půjdete do Ovládacích panelů \> Odinstalovat program.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="1ad2a-115">Pokud narazíte na problémy, odinstalujte pomocí [Pomocníka pro podporu a obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="1ad2a-116">Na serveru RDS se přihlaste do Centra pro správu Microsoftu 365 pomocí účtu správce a [nainstalujte aplikace Microsoft 365 Apps pro podniky](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="1ad2a-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Microsoft 365 Apps for enterprise](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="1ad2a-117">Po instalaci Office ***neotevírejte ani nepřihlašovat*** žádné aplikace Office.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="1ad2a-118">Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:</span><span class="sxs-lookup"><span data-stu-id="1ad2a-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="1ad2a-119">Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte Spustit.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="1ad2a-120">Do pole Otevřít zadejte **regedit**a pak vyberte OK.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="1ad2a-121">Po zobrazení výzvy vyberte Ano, aby Editor registru povolil provádění změn v zařízení.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="1ad2a-122">V Editoru registru přidejte řetězcovou **hodnotu SharedComputerLicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="1ad2a-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="1ad2a-123">Na serveru RDS ***se přihlaste jako koncový uživatel*** a [ověřte, zda je povolena aktivace sdíleného počítače pro aplikace Microsoft 365 Apps pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span><span class="sxs-lookup"><span data-stu-id="1ad2a-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span></span>

<span data-ttu-id="1ad2a-124">Další podrobnosti o požadavcích, pokynech k instalaci a pokynech k přizpůsobeným instalacím pomocí Nástroje pro nasazení office naleznete v [tématu Nasazení aplikací Microsoft 365 pro podniky pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="1ad2a-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Microsoft 365 Apps for enterprise by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span></span>
  
<span data-ttu-id="1ad2a-125">Informace o opravě chyb souvisejících s aktivací sdíleného počítače naleznete [v tématu Řešení problémů s aktivací sdíleného počítače pro aplikace Microsoft 365 Pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="1ad2a-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span></span>
  
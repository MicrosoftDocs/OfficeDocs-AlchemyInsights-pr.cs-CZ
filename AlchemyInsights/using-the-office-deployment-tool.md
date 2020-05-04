---
title: Použití nástroje pro nasazení Office
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: d941bce524dc797d5dcbb7213bded6919fd01b7d
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010850"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="bde0c-102">Použití nástroje pro nasazení sady Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="bde0c-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="bde0c-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span><span class="sxs-lookup"><span data-stu-id="bde0c-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span></span> <span data-ttu-id="bde0c-104">Nástroj pro nasazení sady Office (setup.exe) je spuštěn z příkazového řádku a používá konfigurační soubor XML k určení nastavení, která mají být použita při nasazování Sady Office.</span><span class="sxs-lookup"><span data-stu-id="bde0c-104">The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="bde0c-105">Stáhněte si nejnovější verzi nástroje Pro nasazení sady Office ze [služby Stažení softwaru](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="bde0c-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>

2. <span data-ttu-id="bde0c-106">Pomocí [Nástroje pro přizpůsobení Office (OCT)](https://config.office.com) vyberte předvolby nasazení a vytvořte konfigurační soubor XML.</span><span class="sxs-lookup"><span data-stu-id="bde0c-106">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file.</span></span> <span data-ttu-id="bde0c-107">Exportujte konfigurační soubor a umístěte jej místně do stejné složky, ve které se nachází soubor setup.exe.</span><span class="sxs-lookup"><span data-stu-id="bde0c-107">Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span>

    <span data-ttu-id="bde0c-108">**Poznámka:** K problémům s instalací sady Office obvykle dochází z důvodu chybně nakonfigurovaných nebo neformátovaných konfiguračních souborů.</span><span class="sxs-lookup"><span data-stu-id="bde0c-108">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files.</span></span> <span data-ttu-id="bde0c-109">Chcete-li se těmto problémům vyhnout, doporučujeme k vytvoření konfiguračního souboru použít nástroj pro přizpůsobení sady Office.</span><span class="sxs-lookup"><span data-stu-id="bde0c-109">To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file.</span></span> <span data-ttu-id="bde0c-110">Do Nástroje pro vlastní nastavení Office můžete také importovat existující konfigurační soubory.</span><span class="sxs-lookup"><span data-stu-id="bde0c-110">You can also import existing configuration files into the Office Customization Tool.</span></span>

3. <span data-ttu-id="bde0c-111">Z příkazového řádku se zvýšenými oprávněními přepněte do umístění, kde se nachází soubor setup.exe, a spusťte nástroj pro nasazení sady Office v režimu stahování a zadejte konfigurační soubor, který jste právě uložili.</span><span class="sxs-lookup"><span data-stu-id="bde0c-111">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved.</span></span> <span data-ttu-id="bde0c-112">V tomto příkladu se konfigurační soubor nazývá Configuration.xml:</span><span class="sxs-lookup"><span data-stu-id="bde0c-112">In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="bde0c-113">Spusťte nástroj pro nasazení sady Office v režimu konfigurace a určete konfigurační soubor.</span><span class="sxs-lookup"><span data-stu-id="bde0c-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="bde0c-114">**Poznámka:** Tento krok je nutné spustit z klientského počítače, do kterého chcete nainstalovat sadu Office, a musíte mít v tomto počítači oprávnění místního správce.</span><span class="sxs-lookup"><span data-stu-id="bde0c-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span>

<span data-ttu-id="bde0c-115">Další informace o používání Nástroje pro nasazení Office pro scénáře nasazení aplikací Microsoft 365 pro podnikové nasazení najdete [v tématu Přehled Nástroje pro nasazení Office](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bde0c-115">To learn more about using Office Deployment Tool for your Microsoft 365 Apps for enterprise deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool).</span></span> <span data-ttu-id="bde0c-116">Další podrobnosti o použití Nástroje pro přizpůsobení Office naleznete v [tématu Přehled nástroje pro přizpůsobení Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="bde0c-116">For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>

---
title: Otázky týkající se použití nástroje pro nasazení sady Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 4aef42df4dde17d15863fca67e41f0ff23e506dc
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010724"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="96a07-102">Otázky týkající se použití nástroje pro nasazení sady Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="96a07-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="96a07-103">Stáhněte nástroj pro nasazení sady Office ze [služby Stažení softwaru](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="96a07-103">Download the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="96a07-104">Po stažení souboru spusťte samorozbalovací spustitelný soubor, který obsahuje spustitelný soubor nástroje pro nasazení sady Office (setup.exe) a ukázkový konfigurační soubor (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="96a07-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="96a07-105">**Vyloučení nebo odebrání aplikací Microsoft 365 pro podnikové produkty z klientských počítačů:**</span><span class="sxs-lookup"><span data-stu-id="96a07-105">**To exclude or remove Microsoft 365 Apps for enterprise products from client computers:**</span></span>
  
<span data-ttu-id="96a07-106">Při instalaci aplikací Microsoft 365 pro podniky můžete vyloučit konkrétní produkty.</span><span class="sxs-lookup"><span data-stu-id="96a07-106">When installing Microsoft 365 Apps for enterprise, you can exclude specific products.</span></span> <span data-ttu-id="96a07-107">Chcete-li tak učinit, postupujte podle pokynů pro instalaci Office s ODT, ale zahrnout ExcludeApp prvek v konfiguračním souboru.</span><span class="sxs-lookup"><span data-stu-id="96a07-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="96a07-108">Tento konfigurační soubor například nainstaluje všechny aplikace Microsoft 365 pro podnikové produkty s výjimkou aplikace Publisher:</span><span class="sxs-lookup"><span data-stu-id="96a07-108">For example, this configuration file installs all the Microsoft 365 Apps for enterprise products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="96a07-109">Přehled nástroje pro nasazení Office</span><span class="sxs-lookup"><span data-stu-id="96a07-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  


---
title: Poradce při potížích bezpečnost tip pro detekci podvodů kontroly
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 24842e8cc5c6e47fb0eb637e6a3211637ede1ed8
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29462925"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="e7376-102">Poradce při potížích bezpečnost tip pro detekci podvodů kontroly</span><span class="sxs-lookup"><span data-stu-id="e7376-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="e7376-p101">Získání bezpečnostní tip, který říká "odesílatel nepodařilo naše kontroly detekce podvodů a který se zdá být nemusí být", pak odesílatel projdou kontrolami SPF nebo DKIM ověření se nezdařilo. Nejlepším způsobem vyřešit je pro odesílatele ověřit sami. Pokud odesílatel posílá vaším jménem, je třeba je povolit přidáním IP adresu odesílatele k záznamu SPF.</span><span class="sxs-lookup"><span data-stu-id="e7376-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="e7376-106">Další informace naleznete v tématu [Poradce při potížích s červenou (podezřelé) bezpečnost tip pro detekci podvodů kontroluje](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="e7376-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="e7376-107">Zde jsou některé odkazy, které vám mohou pomoci:</span><span class="sxs-lookup"><span data-stu-id="e7376-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="e7376-108">Použití zásad framework odesílatele (PSPM) Chcete-li zabránit falšování služeb Office 365</span><span class="sxs-lookup"><span data-stu-id="e7376-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/en-us/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- <span data-ttu-id="e7376-109">[Nastavení specifikace SPF v Office 365 jako prevence falšování identity](https://docs.microsoft.com/en-us/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing).</span><span class="sxs-lookup"><span data-stu-id="e7376-109">[Set up SPF in Office 365 to help prevent spoofing](https://docs.microsoft.com/en-us/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)</span></span>
    


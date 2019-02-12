---
title: 1065 odmítání příznaku EOP odchozí IP adresy rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 2b4b2e2341f45e2d37713d72a2e0d34fa1a9a7cc
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29934877"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="8faf9-102">Odmítání příznaku rozsahů adres IP pro odchozí EOP</span><span class="sxs-lookup"><span data-stu-id="8faf9-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="8faf9-p101">Zjistili jsme potenciální problém s organizaci (26. října 2018 není korigovaná) může porušit tok e-mailů na místní nebo externí cíle. Které dříve oznámila zjednodušit řízení rozsah adres IP, jsme se konsoliduje rozsahy adres IP serveru Exchange Online ochrany (EOP), které slouží k odesílání a přijímání e-mailů mimo služeb Office 365. Naše analýza naznačuje, jeden nebo více externí emailových zdrojů nebo cílů, nakonfigurované v spojnice toku pošty nepřijali připojení IP adresu oblasti uvedeno [zde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="8faf9-p101">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations. As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365. Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="8faf9-106">Působit před 26. října zajistit, aby že tyto zdroje a cíle bude přijímat připojení z [publikované adresy EOP IP](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)a.</span><span class="sxs-lookup"><span data-stu-id="8faf9-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="8faf9-107">Další informace o této změně získáte, že zpráva Centrum účtuje, [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)nebo [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="8faf9-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>
  
 <span data-ttu-id="8faf9-p102">**Poznámka**: Pokud jste dříve používali IP nebo adresu URL publikování pomocí HTML, XML a RSS aktualizace koncového bodu, také měli byste přenést do nové webové služby pro automatizaci tyto typy aktualizací. Další informace naleznete v tématu [kategorie koncového bodu služeb Office 365 a Office 365 IP adresa a adresa URL webové služby](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="8faf9-p102">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates. For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
  


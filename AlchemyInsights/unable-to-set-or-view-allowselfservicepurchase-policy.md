---
title: Zásady AllowSelfServicePurchase nelze nastavit ani zobrazit.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: a9b6e36e8034e71b3e72c49e3cc68a126ef97aca
ms.sourcegitcommit: cb9505f9eca032af3a4194c68d18c91789365690
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/16/2020
ms.locfileid: "42091678"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a><span data-ttu-id="08f77-102">Zásady AllowSelfServicePurchase nelze nastavit ani zobrazit.</span><span class="sxs-lookup"><span data-stu-id="08f77-102">Unable to set or view the AllowSelfServicePurchase policy</span></span>

<span data-ttu-id="08f77-103">Při pokusu o nastavení nebo zobrazení zásad AllowSelfServicePurchase se zobrazí následující chybová zpráva:</span><span class="sxs-lookup"><span data-stu-id="08f77-103">When attempting to set or view the AllowSelfServicePurchase policy, you receive the following error message:</span></span>

<span data-ttu-id="08f77-104">*HandleError : Nepodařilo se načíst zásady produktu s PolicyId 'AllowSelfServicePurchase', ErrorMessage - Základní připojení bylo uzavřeno: Při odesílání došlo k neočekávané chybě.*</span><span class="sxs-lookup"><span data-stu-id="08f77-104">*HandleError : Failed to retrieve product policy with PolicyId 'AllowSelfServicePurchase', ErrorMessage - The underlying connection was closed: An unexpected error occurred on a send.*</span></span>

<span data-ttu-id="08f77-105">To může být způsobeno starší verzí zabezpečení transportní vrstvy (TLS).</span><span class="sxs-lookup"><span data-stu-id="08f77-105">This may be due to an older version of Transport Layer Security (TLS).</span></span> <span data-ttu-id="08f77-106">Chcete-li připojit službu MSCommerce, musíte použít TLS 1.2 nebo vyšší.</span><span class="sxs-lookup"><span data-stu-id="08f77-106">To connect the MSCommerce service, you need to use TLS 1.2 or greater.</span></span>  

<span data-ttu-id="08f77-107">Pomocí následujících kroků povolte nebo nastavte protokol TLS na 1.2, ověřte a opakujte akci.</span><span class="sxs-lookup"><span data-stu-id="08f77-107">Try the following steps to enable/set the TLS protocol to 1.2, verify, and retry.</span></span>
 1. <span data-ttu-id="08f77-108">Na příkazovém řádku Prostředí\) PowerShell (PS C: zadejte následující příkaz pro nastavení protokolu TLS na verzi 1.2:</span><span class="sxs-lookup"><span data-stu-id="08f77-108">At the PowerShell command prompt (PS C:\) enter the following command to set the TLS protocol to version 1.2:</span></span>

    <span data-ttu-id="08f77-109">\[Net.ServicePointManager]::SecurityProtocol = \[Net.SecurityProtocolType]::Tls12</span><span class="sxs-lookup"><span data-stu-id="08f77-109">\[Net.ServicePointManager]::SecurityProtocol = \[Net.SecurityProtocolType]::Tls12</span></span>

2. <span data-ttu-id="08f77-110">Ověřte protokoly TLS, které se používají, pomocí následujícího příkazu:</span><span class="sxs-lookup"><span data-stu-id="08f77-110">Verify the TLS protocol(s) in use, with the following command:</span></span>

    <span data-ttu-id="08f77-111">\[Net.ServicePointManager]::Protokol SecurityProtocol</span><span class="sxs-lookup"><span data-stu-id="08f77-111">\[Net.ServicePointManager]::SecurityProtocol</span></span> 

3. <span data-ttu-id="08f77-112">Podle potřeby opakujte příkazy Získat nebo aktualizovat.</span><span class="sxs-lookup"><span data-stu-id="08f77-112">Retry the Get or Update commands as needed.</span></span>

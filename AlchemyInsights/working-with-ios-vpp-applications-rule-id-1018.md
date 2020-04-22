---
title: Práce s iOS VPP aplikace Id 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 88a1ef66bf337b3a0094976c122330591aee77ff
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719950"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="54e95-102">Práce s aplikacemi vpp iOS</span><span class="sxs-lookup"><span data-stu-id="54e95-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="54e95-103">Přečtěte si [článek Jak spravovat aplikace pro iOS zakoupené v programu pro nákup objemu pomocí Microsoft Intune,](https://docs.microsoft.com/intune/vpp-apps-ios) kde se dozvíte o funkcích, omezeních a krocích, jak využít Program hromadných nákupů Apple a jeho podporu v Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="54e95-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="54e95-104">**Běžné problémy:** "Přiřadil jsem uživatelům aplikaci IOS VPP, ale instalace se nezdařila."</span><span class="sxs-lookup"><span data-stu-id="54e95-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="54e95-105">K tomu může dojít, pokud se jeden token VPP používá mezi více poskytovateli správy mobilních zařízení.</span><span class="sxs-lookup"><span data-stu-id="54e95-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="54e95-106">VPP tokeny od společnosti Apple lze používat pouze s jedním poskytovatelem.</span><span class="sxs-lookup"><span data-stu-id="54e95-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="54e95-107">Pokud jste použili token VPP s více poskytovateli, musíte token znovu nahrát do Intune.</span><span class="sxs-lookup"><span data-stu-id="54e95-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="54e95-108">Instalace může také selhat, pokud celkový počet instalací překročí počet licencí.</span><span class="sxs-lookup"><span data-stu-id="54e95-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="54e95-109">Pokud chcete zobrazit sestavu využití licencí, přejděte na stránku \> **licence aplikací** Pro Aplikace Pro **Aplikace Intune.**</span><span class="sxs-lookup"><span data-stu-id="54e95-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="54e95-110">Informace o tom, jak získat licence, které se používají, najdete v [tomto článku.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="54e95-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>

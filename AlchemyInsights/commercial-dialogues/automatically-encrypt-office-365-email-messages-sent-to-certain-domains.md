---
title: Automatické šifrování e-mailových zpráv Office 365 odeslaných do určitých domén
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 7fb96a30cd1922bd39a4b99a7ecd869622f3a466
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2021
ms.locfileid: "50744549"
---
# <a name="automatically-encrypt-office-365-email-messages-sent-to-certain-domains"></a><span data-ttu-id="bc01e-102">Automatické šifrování e-mailových zpráv Office 365 odeslaných do určitých domén</span><span class="sxs-lookup"><span data-stu-id="bc01e-102">Automatically encrypt Office 365 email messages sent to certain domains</span></span>

1. <span data-ttu-id="bc01e-103">V Centru [pro správu Exchange](https://outlook.office365.com/ecp/)zvolte **tok pošty > pravidla**.</span><span class="sxs-lookup"><span data-stu-id="bc01e-103">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="bc01e-104">Klikněte na **ikonu Nový (+)** a potom klikněte na Použít šifrování zpráv **Office 365** a ochranu práv u zpráv.</span><span class="sxs-lookup"><span data-stu-id="bc01e-104">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="bc01e-105">Do **pole** Název zadejte název pravidla, například Šifrovat zprávy odeslané *contoso.com.*</span><span class="sxs-lookup"><span data-stu-id="bc01e-105">In **Name**, enter a name for the rule, such as *Encrypt messages sent to contoso.com*.</span></span>
4. <span data-ttu-id="bc01e-106">V **části Použít toto pravidlo, pokud** zvolte > doména **je**.</span><span class="sxs-lookup"><span data-stu-id="bc01e-106">In **Apply this rule if**, choose **The recipient > domain is**.</span></span> 
5. <span data-ttu-id="bc01e-107">Zadejte název domény, například **contoso.com**.</span><span class="sxs-lookup"><span data-stu-id="bc01e-107">Enter the name of the domain, such as **contoso.com**.</span></span>
6. <span data-ttu-id="bc01e-108">Klikněte na **ikonu Přidat (+)** a potom klikněte na **OK.**</span><span class="sxs-lookup"><span data-stu-id="bc01e-108">Click the **Add (+)** icon, and then click **OK**.</span></span>
7. <span data-ttu-id="bc01e-109">Vedle pole **Do the following (Provést následující)** klikněte na Select one **(Vybrat jednu).**</span><span class="sxs-lookup"><span data-stu-id="bc01e-109">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="bc01e-110">V rozevírací **nabídce šablony RMS** vyberte Šifrovat a potom klikněte na **OK.** </span><span class="sxs-lookup"><span data-stu-id="bc01e-110">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="bc01e-111">(Pokud tuto možnost nevidíte, znamená to, že váš plán neobsahuje automatické šifrování.</span><span class="sxs-lookup"><span data-stu-id="bc01e-111">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="bc01e-112">Ale můžete ho přidat!)</span><span class="sxs-lookup"><span data-stu-id="bc01e-112">But you can add it!)</span></span>
9. <span data-ttu-id="bc01e-113">Zvolte libovolný volitelný výběr (ze seznamu volitelných výběrů, které můžete v tomto okamžiku provést, z nichž mnohé můžete nechat s výchozím nastavením pro jednoduchost).</span><span class="sxs-lookup"><span data-stu-id="bc01e-113">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="bc01e-114">Klikněte na **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="bc01e-114">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="bc01e-115">Toto pravidlo se můžete vrátit a toto pravidlo upravit později.</span><span class="sxs-lookup"><span data-stu-id="bc01e-115">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="bc01e-116">Další informace o vytváření pravidel pro šifrování najdete v článku Definování pravidel toku pošty pro šifrování e-mailových zpráv [v Office 365.](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span><span class="sxs-lookup"><span data-stu-id="bc01e-116">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span></span>
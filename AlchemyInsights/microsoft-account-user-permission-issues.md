---
title: Odstraňování problémů s problémem-uživatel nenalezen v adresáři
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 59713231da25be441e7c05d788337e66bf17265a
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768794"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="4349e-102">Odstraňování problémů s problémem-uživatel nenalezen v adresáři</span><span class="sxs-lookup"><span data-stu-id="4349e-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="4349e-103">Pokud se uživatelům zobrazuje chybová zpráva "uživatel nebyl nalezen" v adresáři, opakujte akci, pokud je typ problému uživatel není v adresáři.</span><span class="sxs-lookup"><span data-stu-id="4349e-103">If users are receiving error message "user can't be found" in the directory, please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="4349e-104">K vyřešení problému lze provést následující kroky.</span><span class="sxs-lookup"><span data-stu-id="4349e-104">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="4349e-105">Ujistěte se, že účet, který přijal e-mailovou pozvánku, je stejný účet, který se používá k pozdějšímu přihlášení.</span><span class="sxs-lookup"><span data-stu-id="4349e-105">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="4349e-106">Ujistěte se, že uživatel používá stejný účet k přijmutí pozvání a přihlášení na web.</span><span class="sxs-lookup"><span data-stu-id="4349e-106">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="4349e-107">Další informace naleznete v tématu [Správa aliasů pro účet</a> společnosti Microsoft za účelem správy sady Office 365 Login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="4349e-107">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="4349e-108">Přejděte na každý web (y), ve kterém uživatel chybu obdržel.</span><span class="sxs-lookup"><span data-stu-id="4349e-108">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="4349e-109">Přidejte "/_layouts/15/People.aspx/MembershipGroupId = 0" (v rámci uvozovek) na konec adresy URL webu.</span><span class="sxs-lookup"><span data-stu-id="4349e-109">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="4349e-110">Příklad: https://< "contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="4349e-110">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="4349e-111">Vyberte uživatele ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="4349e-111">Select the user from the list.</span></span>

- <span data-ttu-id="4349e-112">Klepněte na tlačítko **Odebrat oprávnění uživatele** z pásu karet.</span><span class="sxs-lookup"><span data-stu-id="4349e-112">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="4349e-113">Přidejte uživatele zpět a znovu odešlete pozvání uživateli.</span><span class="sxs-lookup"><span data-stu-id="4349e-113">Add back the User and Resend the invite to the user.</span></span>


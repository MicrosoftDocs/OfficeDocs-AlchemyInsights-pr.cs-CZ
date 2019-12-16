---
title: Seznámení s webem služby SharePoint Online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 285c580d69efb369fa6a60066165123e3c91b0a7
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051634"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="c9392-102">Pracovní postupy ve službě SharePoint</span><span class="sxs-lookup"><span data-stu-id="c9392-102">Workflows in SharePoint</span></span>

<span data-ttu-id="c9392-103">Pokud pracovní postupy služby SharePoint neodesílají e-maily, je možné, že vaše organizace narazila na omezení odesílatele serveru Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c9392-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="c9392-104">Pokud máte některou z následujících položek, může se zobrazit chybová zpráva pracovní postup je pozastaven:</span><span class="sxs-lookup"><span data-stu-id="c9392-104">The 'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="c9392-105">Ve službě SharePoint Online máte pracovní postup, který používá typ platformy SharePoint 2010 nebo SharePoint 2013 Workflow.</span><span class="sxs-lookup"><span data-stu-id="c9392-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="c9392-106">Pracovní postup je konfigurován tak, aby odeslal vlastní e-mailovou zprávu více než 200 uživatelům najednou, více než 10 000 příjemců za den nebo více než 30 zpráv za minutu.</span><span class="sxs-lookup"><span data-stu-id="c9392-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="c9392-107">Pokud pracovní postup spustíte, nebude e-mailová zpráva odeslána a zobrazí se chybová zpráva, je v poli vnitřní stav nastavena na pozastaveno nebo není možné odeslat zprávu příjemci.</span><span class="sxs-lookup"><span data-stu-id="c9392-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="c9392-108">Další informace naleznete v následujícím [článku](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).</span><span class="sxs-lookup"><span data-stu-id="c9392-108">For more information, please refer to the following [article](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).</span></span>


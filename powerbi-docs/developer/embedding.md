---
title: Power BI 的內嵌功能
description: Power BI 提供 API 來將您的儀表板和報表內嵌至應用程式。
author: markingmyname
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-developer
ms.topic: overview
ms.date: 07/31/2018
ms.author: maghan
ms.openlocfilehash: 8f200450e5359124ffcc3447c68c6bd755c57896
ms.sourcegitcommit: fecea174721d0eb4e1927c1116d2604a822e4090
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/31/2018
ms.locfileid: "39359855"
---
# <a name="embedding-with-power-bi"></a>Power BI 的內嵌功能
Power BI 服務 (SaaS) 和 Azure 中的 Power BI Embedded 服務 (PaaS) 都有 API 可供內嵌您的儀表板和報表。 這意謂著在內嵌內容時，您會有一組功能可供使用，並可存取最新的 Power BI 功能，例如儀表板、閘道及應用程式工作區。

您可以完成[上線體驗工具](https://aka.ms/embedsetup)以快速開始使用並下載應用程式範例。

選擇最適合您的方案：

* [對組織進行內嵌](embedding.md#embedding-for-your-organization)可讓您擴充 Power BI 服務。 執行[對組織進行內嵌](https://aka.ms/embedsetup/UserOwnsData)解決方案。
* [對客戶進行內嵌](embedding.md#embedding-for-your-customers)，可讓您將儀表板和報告內嵌至沒有 Power BI 帳戶的使用者。 執行[對客戶進行內嵌](https://aka.ms/embedsetup/AppOwnsData)解決方案。

![PBIE 範例](media/what-can-you-do/what-can-you-do-02.png)

## <a name="using-apis"></a>使用 API
內嵌 Power BI 內容時有兩個主要案例。  內嵌貴組織中有 Power BI 授權的使用者，以及內嵌使用者和客戶而不要求他們有 Power BI 授權。 這兩個案例都允許使用 Power BI REST API。

針對沒有 Power BI 授權的客戶和使用者，將儀表板和報告內嵌至您的自訂應用程式，並使用相同的 API 來服務組織或客戶。 您的客戶會看到應用程式所管理的資料。 此外，針對組織中的 Power BI 使用者，他們將可另外選擇要直接在 Power BI 中，還是在內嵌應用程式內容中檢視「他們的資料」。 您可以針對內嵌需求而完整利用 JavaScript 和 REST API。

若要檢視內嵌運作方式的範例，請參閱 [JavaScript 內嵌範例](https://microsoft.github.io/PowerBI-JavaScript/demo/)。

## <a name="embedding-for-your-organization"></a>對組織進行內嵌
**對組織進行內嵌**可讓您擴充 Power BI 服務。 當應用程式的使用者需要檢視其內容時，就需要登入 Power BI 服務。 貴組織中有人登入之後，他們只能在 Power BI 服務中存取他們自己的和已經與他們共用的儀表板和報告。

*對組織進行內嵌的範例包括內部 Web 應用程式、SharePoint Online 網頁組件和 [Microsoft Teams 整合 (您必須具有管理員權限)](https://powerbi.microsoft.com/en-us/blog/power-bi-teams-up-with-microsoft-teams/)。*

若要對組織進行內嵌，請參閱下列文章：

* [將報表整合到應用程式](embed-sample-for-your-organization.md)

針對 Power BI 使用者內嵌時，可透過 [JavaScript API](https://github.com/Microsoft/PowerBI-JavaScript) 來使用自助功能，例如編輯、儲存等。

您可以透過對組織進行內嵌的[入門訓練體驗工具](https://aka.ms/embedsetup/UserOwnsData) \(英文\) 來快速開始及下載範例應用程式，該應用程式會引導您整合組織的報表。

## <a name="embedding-for-your-customers"></a>對客戶進行內嵌

**對客戶進行內嵌**，可讓您將儀表板和報告內嵌至沒有 Power BI 帳戶的使用者。 您的客戶完全不需要了解 Power BI。 若要建立內嵌的應用程式，至少需要一個 Power BI Pro 帳戶。 Power BI Pro 帳戶將成為應用程式的主帳戶。 將這個當作 Proxy 帳戶。 Power BI Pro 帳戶也可讓您產生內嵌權杖，以提供存取 Power BI 服務內應用程式所擁有/管理的儀表板和報告。

[Power BI Embedded](azure-pbie-what-is-power-bi-embedded.md) 為獨立軟體廠商 (ISV) 和開發人員提供針對客戶進行內嵌的功能，其可透過以容量為基礎的每小時計量付費模型，將令人讚嘆的視覺效果、報表和儀表板快速新增至應用程式中。

![對客戶進行內嵌的內嵌流程](media/embedding/powerbi-embed-flow.png)

Power BI Embedded 可為 ISV、其開發人員及客戶帶來好處。 例如，ISV 可以免費使用 Power BI Desktop 開始建立視覺效果。 ISV 可以藉由減少視覺效果分析開發工作並利用差異化的資料體驗在競爭對手中脫穎而出，加快應用程式上市的速度。 ISV 也可以選擇針對內嵌分析創造的價值收取較高的費用。

開發人員可以花時間專注在建置其應用程式的核心競爭力，而不是將時間耗費在開發視覺效果和分析。 開發人員可以快速滿足客戶報表和儀表板的需求，並且能夠輕鬆地內嵌完整記載的 API 和 SDK。 最後，透過在其應用程式中啟用輕鬆巡覽資料探勘，ISV 可讓其客戶在內容中進行快速、資料驅動的決策，並且可以放心地從任何裝置進行。

> [!IMPORTANT]
> 雖然內嵌相依於 Power BI 服務，但客戶不相依於 Power BI。 他們不需要註冊 Power BI，即可檢視應用程式中的內嵌內容。

當您準備好進入生產環境時，必須將應用程式工作區指派給專屬的容量。 Microsoft Azure 中的 Power BI Embedded 提供與您應用程式搭配使用的專屬容量。

如需有關如何內嵌的詳細資訊，請參閱[如何內嵌 Power BI 儀表板、報告和圖格](embed-sample-for-customers.md)。

您可以透過[入門訓練體驗工具](https://aka.ms/embedsetup/AppOwnsData) \(英文\) 來快速開始及下載範例應用程式，該應用程式會引導您將報表整合至您的應用程式。

如果您在 Azure 內使用 Power BI 工作區集合服務，請參閱[從 Power BI 工作區集合 Azure 服務移轉內容](migrate-from-powerbi-embedded.md)以取得如何移轉內容的資訊。

## <a name="next-steps"></a>後續步驟
現在，您可以嘗試將 Power BI 內容內嵌至應用程式，或嘗試對您的客戶內嵌 Power BI 內容。

> [!div class="nextstepaction"]
> [什麼是 Power BI Embedded？](azure-pbie-what-is-power-bi-embedded.md)

> [!div class="nextstepaction"]
> [為組織內嵌](embed-sample-for-your-organization.md)

> [!div class="nextstepaction"]
>[對客戶進行內嵌](embed-sample-for-customers.md)

有其他問題嗎？ [嘗試在 Power BI 社群提問](http://community.powerbi.com/)
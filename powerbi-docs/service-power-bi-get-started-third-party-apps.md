---
title: Power BI 開始使用協力廠商應用程式
description: Power BI 開始使用協力廠商應用程式
author: markingmyname
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-service
ms.topic: conceptual
ms.date: 08/10/2017
ms.author: maghan
LocalizationGroup: Get started
ms.openlocfilehash: 7ac6cee3331333b40119d6f5ab014b2e39d2ef23
ms.sourcegitcommit: 80d6b45eb84243e801b60b9038b9bff77c30d5c8
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/04/2018
ms.locfileid: "34251741"
---
# <a name="get-started-with-third-party-apps"></a>開始使用協力廠商應用程式
有了 Power BI，您就可以使用 Microsoft 以外的公司或個人所建置的應用程式。 例如，您可能會使用將 Power BI 磚整合到自訂建置 Web 應用程式的協力廠商應用程式。 當您使用協力廠商應用程式時，系統會要求您將 Power BI 帳戶和資源特定權限授與該應用程式。 請務必只將權限授予給您已知且信任的應用程式。 應用程式的權限可以隨時撤銷。 請參閱[撤銷協力廠商應用程式權限](#revoke).

以下是應用程式可以要求的存取權類型。

## <a name="power-bi-app-permissions"></a>Power BI 應用程式權限
* **檢視所有儀表板**
  
  * 此權限可讓應用程式檢視所有您可存取的儀表板。 這包括您所擁有的儀表板、從內容套件取得的儀表板，以及位於您所屬群組中且與您共用的儀表板。 應用程式無法對儀表板進行任何修改。 在其他方面，應用程式可使用此權限，將您的儀表板內容內嵌至其經驗。
* **檢視所有報表**
  
  * 此權限可讓應用程式檢視所有您可存取的報表。 這包括您所擁有的報表、從內容套件取得的報表，以及位於您所屬群組中的報表。 檢視報表時，表示應用程式也可以查看其中的資料。 應用程式無法對報表本身進行任何修改。 在其他方面，應用程式可使用此權限，將您的報表內容內嵌至其經驗。
* **檢視所有資料集**
  
  * 此權限可讓應用程式列出所有您可存取的資料集。 這包括您所擁有的資料集、從內容套件取得的資料集，以及位於您所屬群組中的資料集。 應用程式可以看到您的資料集以及其結構，包括資料表與資料行的名稱。 此權限可用以讀取資料集中的資料。 此權限並不會讓應用程式加入或變更資料集。
* **讀取和寫入所有資料集**
  
  * 此權限可讓應用程式列出所有您可存取的資料集。 這包括您所擁有的資料集、從內容套件取得的資料集，以及位於您所屬群組中的資料集。 應用程式可以看到您的資料集以及其結構，包括資料表與資料行的名稱。 此權限可用以讀取及寫入資料集中的資料。 應用程式也可以建立新的資料集，或修改現有資料集。 應用程式若要直接將資料傳送到 Power BI，通常會使用此方式。
* **檢視使用者群組**
  
  * 此權限可讓應用程式列出所有您所屬的群組。 其可以使用列出的其他權限及此權限，進而檢視或更新該特定群組的內容。 應用程式無法對群組本身進行任何修改。

<a name="revoke"/>

## <a name="revoke-third-party-app-permissions"></a>撤銷協力廠商應用程式權限
請前往 Office 365 我的應用程式網站以撤銷協力廠商應用程式的權限。

在 **Office 365 我的應用程式** 網站，撤銷協力廠商權限的方式如下：

1. 前往 [Office 365 我的應用程式網站](https://portal.office.com/myapps).
2. 在 [我的應用程式]  頁面上找到協力廠商應用程式。
3. 將滑鼠暫留在該應用程式的磚，按一下 [(...)]  按鈕，然後按一下 [移除] 。
   
   ![](media/service-power-bi-get-started-third-party-apps/remove.png)


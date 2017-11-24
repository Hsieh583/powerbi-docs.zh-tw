---
title: "Power BI 的資料列層級安全性 (RLS)"
description: "如何在 Power BI 服務內設定匯入資料集的資料列層級安全性和 DirectQuery。"
services: powerbi
documentationcenter: 
author: guyinacube
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: no
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: powerbi
ms.date: 08/11/2017
ms.author: asaxton
ms.openlocfilehash: ea51308d533dc97af9d06855d004b5bacc376247
ms.sourcegitcommit: 99cc3b9cb615c2957dde6ca908a51238f129cebb
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/13/2017
---
# <a name="row-level-security-rls-with-power-bi"></a>Power BI 的資料列層級安全性 (RLS)
<iframe width="560" height="315" src="https://www.youtube.com/embed/67fK0GoVQ80?showinfo=0" frameborder="0" allowfullscreen></iframe>

Power BI 的資料列層級安全性 (RLS) 可用以限制指定使用者的資料存取。 篩選會限制資料列層級的資料。 您可以在角色中定義篩選。

您可以使用 Power BI Desktop 為匯入 Power BI 的資料模型設定 RLS。 您也可以針對使用 DirectQuery (如 SQL Server) 的資料集設定 RLS。 先前，您只能夠在 Power BI 外部的內部部署 Analysis Services 模型實作 RLS。 您可以在內部部署模型上，為 Analysis Services 即時連線設定資料列層級安全性。 即時連線資料集不會顯示安全性選項。

[!INCLUDE [include-short-name](./includes/rls-desktop-define-roles.md)]

[!INCLUDE [include-short-name](./includes/rls-desktop-view-as-roles.md)]

## <a name="manage-security-on-your-model"></a>管理模型的安全性
若要管理資料模型的安全性，需要執行下列動作。

1. 針對資料集選取**省略符號 (...)**。
2. 選取 [安全性]。
   
   ![](media/service-admin-rls/rls-security.png)

這樣會帶您到 RLS 頁面上，以將成員加入您在 Power BI Desktop 中建立的角色。 只有資料集的擁有者會看到 [安全性] 可供使用。 如果資料集是在群組中，只有群組的系統管理員會看到安全性選項。 

您只能在 Power BI Desktop 中建立或修改角色。

## <a name="working-with-members"></a>使用成員
### <a name="add-members"></a>新增成員
您可以輸入想要新增的使用者、安全性群組或通訊群組清單的電子郵件地址或名稱，將成員加入角色中。 這個成員必須是貴組織的成員。 您無法加入在 Power BI 中建立的群組。

![](media/service-admin-rls/rls-add-member.png)

您也可以根據角色名稱或 [成員] 旁括弧內的數字，知道有多少成員屬於該角色。

![](media/service-admin-rls/rls-member-count.png)

### <a name="remove-members"></a>移除成員
您可以選取成員名稱旁的 X 來移除成員。 

![](media/service-admin-rls/rls-remove-member.png)

## <a name="validating-the-role-within-the-power-bi-service"></a>在 Power BI 服務中驗證角色
您可以測試角色以驗證您定義的角色是否正常運作。 

1. 選取角色旁的**省略符號 (...)**。
2. 選取 [以角色測試資料]。

![](media/service-admin-rls/rls-test-role.png)

就會看到這個角色可以使用的報表。 這個檢視未顯示儀表板。 在上方的藍色列中，您會看到套用的功能。

![](media/service-admin-rls/rls-test-role2.png)

您可以選取 \[Now viewing as] \(現在檢視為) 來測試其他角色或角色組合。

![](media/service-admin-rls/rls-test-role3.png)

您可以選擇以特定人員身分檢視資料，或者選取可用的角色組合來驗證它們是否作用。 

若要返回正常檢視，請選取 [返回資料列層級安全性]。

[!INCLUDE [include-short-name](./includes/rls-usernames.md)]

## <a name="using-rls-with-app-workspaces-in-power-bi"></a>在 Power BI 中對應用程式工作區使用 RLS
如果您將 Power BI Desktop 報告發佈至 Power BI 服務內的應用程式工作區，角色會套用至唯讀成員。 您必須在應用程式工作區設定內指出成員只能檢視 Power BI 內容。

> [!WARNING]
> 如果您已將應用程式工作區設定為讓成員具有編輯權限，則 RLS 角色不會套用至成員。 使用者可以查看所有的資料。
> 
> 

![](media/service-admin-rls/rls-group-settings.png)

[!INCLUDE [include-short-name](./includes/rls-limitations.md)]

[!INCLUDE [include-short-name](./includes/rls-faq.md)]

## <a name="next-steps"></a>後續步驟
[使用 Power BI Desktop 的資料列層級安全性 (RLS)](desktop-rls.md)  

有其他問題嗎？ [嘗試在 Power BI 社群提問](http://community.powerbi.com/)

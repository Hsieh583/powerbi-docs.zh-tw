---
title: 在 Power BI Desktop 中連線至 Impala 資料庫
description: 在 Power BI Desktop 中輕鬆連接到 Impala 資料庫並加以使用
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 07/27/2018
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: 781e9f6813fee63b7c5d83a2e7e60e1ed1eeedc0
ms.sourcegitcommit: f01a88e583889bd77b712f11da4a379c88a22b76
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/27/2018
ms.locfileid: "39326985"
---
# <a name="connect-to-an-impala-database-in-power-bi-desktop"></a>在 Power BI Desktop 中連線至 Impala 資料庫
在 Power BI Desktop 中，您可以連接至 **Impala 資料庫**並使用基礎資料，就像 Power BI Desktop 中的任何其他資料來源。

## <a name="connect-to-an-impala-database"></a>連接到 Impala 資料庫
若要連線至 **Impala** 資料庫，請從 Power BI Desktop 的 [首頁] 功能區選取 [取得資料]。 從左側類別中選取 [資料庫]，您就會看到 [Impala]。

![](media/desktop-connect-impala/connect_impala_2.png)

在顯示的 [Impala] 視窗中，將您的 Impala 伺服器名稱鍵入或貼上方塊中，然後選取 [確定]。 請注意，您可以選擇直接將資料 [匯入] Power BI 中，也可以使用 [DirectQuery]。 您可以深入了解[如何使用 DirectQuery](desktop-use-directquery.md)。

![](media/desktop-connect-impala/connect_impala_3a.png)

出現提示時，輸入您的認證，或以匿名方式連線。 Impala 連接器支援匿名、基本 (使用者名稱 + 密碼) 和 Windows 驗證。

![](media/desktop-connect-impala/connect_impala_4.png)

> [!NOTE]
> 一旦您在特定 **Impala** 伺服器放入使用者名稱和密碼，Power BI Desktop 便會在後續連接嘗試中使用與其相同的認證。 您可以前往 **[檔案] > [選像和設定] > [資料來源設定]** 修改認證。
> 
> 

成功連接後，[導覽器] 視窗隨即出現，並顯示伺服器上可用的資料，您可以從中選取一或多個要匯入 **Power BI Desktop** 並在其中使用的項目。

![](media/desktop-connect-impala/connect_impala_5.png)

## <a name="considerations-and-limitations"></a>考量與限制
使用 **Impala** 連接器時，有幾項限制和考量必須注意：

* 內部部署資料閘道支援 Impala 連接器，使用三種支援的驗證機制中的任何一種。

## <a name="next-steps"></a>後續步驟
您可以使用 Power BI Desktop 連接至各式各樣的資料。 如需有關資料來源的詳細資訊，請參閱下列資源︰

* [Power BI Desktop 是什麼？](desktop-what-is-desktop.md)
* [Power BI Desktop 中的資料來源](desktop-data-sources.md)
* [使用 Power BI Desktop 合併資料並使其成形](desktop-shape-and-combine-data.md)
* [在 Power BI Desktop 中連接至 Excel 活頁簿](desktop-connect-excel.md)   
* [直接將資料輸入 Power BI Desktop 中](desktop-enter-data-directly-into-desktop.md)   


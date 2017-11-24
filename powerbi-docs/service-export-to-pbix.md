---
title: "將報表從 Power BI 服務匯出至 Desktop (預覽)"
description: "從 Power BI 服務將報表下載到 Power BI Desktop 檔案"
services: powerbi
documentationcenter: 
author: mihart
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: no
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 09/27/2017
ms.author: mihart
ms.openlocfilehash: 30975e9192633043aed7e4196820ef34044b8fcb
ms.sourcegitcommit: 99cc3b9cb615c2957dde6ca908a51238f129cebb
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/13/2017
---
# <a name="export-a-report-from-power-bi-service-to-desktop-preview"></a>將報表從 Power BI 服務匯出至 Desktop (預覽)
在 Power BI Desktop 中，您可以匯出 (也稱為「下載」) 報表至 Power BI 服務，方法是儲存報表，並選取 [發佈]。 您也可以另一個方向來匯出，並從 Power BI 服務下載報表到 Desktop。 在任一方向中，匯出的檔案副檔名為 *.pbix* 。

有幾項需要注意的限制和考量，將在本文稍後討論。

![](media/service-export-to-pbix/power-bi-file-export.png)

## <a name="download-the-report-as-a-pbix"></a>將報表下載為 .pbix
若要下載 .pbix 檔案，請遵循下列步驟：

1. 在 [Power BI 服務] 中，以[編輯檢視](service-reading-view-and-editing-view.md)開啟您想要下載的報表。
2. 從功能表列中，選取 [檔案] > [下載報表]。
   
   > [!NOTE]
   > 報表必須在 2016 年 11 月 23 日後[使用 Power BI Desktop 建立](guided-learning/publishingandsharing.yml#step-2)，或在那之後更新，才能下載報表。 如果沒有，Power BI 服務中的「下載報表」功能表選項會是灰色。
   > 
   > 
3. 建立 .pbix 檔案時，狀態橫幅會顯示進度。 當檔案已準備就緒時，系統會要求您開啟或儲存 .pbix 檔案。 檔案名稱與報表標題相符。
   
    ![](media/service-export-to-pbix/power-bi-save-pbix.png)
   
    您現在有使用 Power BI 服務 (app.powerbi.com) 或 Power BI Desktop 開啟 .pbix 檔案的選項。     
4. 若要立即在 Desktop 中開啟報表，請選取 [開啟]。  如果您還沒有這麼做，請[安裝 Power BI Desktop](desktop-get-the-desktop.md)。
   
    當您在 Desktop 中開啟報表時，警告訊息可讓您了解 Power BI 服務報表的某些功能可能無法用於 Desktop。
   
    ![](media/service-export-to-pbix/power-bi-export-to-pbix_2.png)
5. 若要在 Power BI 服務中開啟報表，請選取 [儲存]，然後使用 [取得資料] 巡覽至您儲存 .pbix 檔案的位置。
   
    ![](media/service-export-to-pbix/power-bi-get-data.png)

## <a name="considerations-and-troubleshooting"></a>考量與疑難排解
從 Power BI 服務下載 (匯出) *.pbix* 檔案有幾項重要的相關考量和限制。

* 若要下載檔案，您必須要有報表的編輯存取權
* 報表必須已從 **Power BI Desktop** 產生並「發佈」到 **Power BI 服務**，或是必須已將 .pbix「上傳」到服務。
* 報表必須在 2016 年 11 月 23 日之後發佈或更新。 在這之前發佈的報表無法下載。
* 此功能無法對原先是在 **Power BI 服務**中建立的報表運作，包括內容套件。
* 開啟下載的檔案時，應一律使用最新版本的 **Power BI Desktop**。 下載的 *.pbix* 檔案無法在舊版 **Power BI Desktop** 中開啟。
* 如果您的系統管理員已關閉匯出資料的功能，在 **Power BI 服務**中就不會看到此功能。

## <a name="next-steps"></a>後續步驟
檢視 **Guy in a Cube** 關於此功能的一分鐘影片：

<iframe width="560" height="315" src="https://www.youtube.com/embed/ymWqU5jiUl0" frameborder="0" allowfullscreen></iframe>

此外，以下其他幾篇文章可以協助您了解如何使用 **Power BI 服務**：

* [Power BI 中的報表](service-reports.md)
* [Power BI - 基本概念](service-basic-concepts.md)

一旦安裝 **Power BI Desktop**，下列內容能幫助您快速啟動並執行：

* [開始使用 Power BI Desktop](desktop-getting-started.md)

有其他問題嗎？ [試試 Power BI 社群](http://community.powerbi.com/)   

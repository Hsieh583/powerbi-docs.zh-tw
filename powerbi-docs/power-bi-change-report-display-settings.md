---
title: "變更報表頁面的大小 (教學課程)"
description: "教學課程：變更 Power BI 報表中頁面的顯示設定"
services: powerbi
documentationcenter: 
author: mihart
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: modifying
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 10/25/2017
ms.author: mihart
ms.openlocfilehash: a5cc05e26012f88e889612788d4479a370063d4f
ms.sourcegitcommit: 99cc3b9cb615c2957dde6ca908a51238f129cebb
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/13/2017
---
# <a name="change-the-size-of-a-report-page-tutorial"></a>變更報表頁面的大小 (教學課程)
在[前一篇文章及前一部影片](power-bi-report-display-settings.md)中，您學到兩種不同的方式來控制在 Power BI 報表中的頁面顯示：**檢視**和**頁面大小**。 現在讓我們來試試看吧！

## <a name="first-lets-change-the-page-view-setting"></a>首先，我們要來變更此頁面的檢視設定
1. 以閱讀檢視或編輯檢視開啟報表。 此範例使用[零售分析範例](sample-retail-analysis.md)的 [新門市] 頁面。  此頁面是使用 [調整成一頁] 設定加以顯示。  在此情況下，調整成一頁會顯示沒有捲軸的報表頁面，但某些詳細資料與標題會太小而無法讀取。
   
   ![](media/power-bi-change-report-display-settings/pbi_fit_to_page.png)
2. 請確定在畫布上未選取任何視覺效果。 選取 [檢視]  並檢閱顯示選項。

* 在 [閱讀] 檢視中您會看到這個項目。
  
     ![](media/power-bi-change-report-display-settings/power-bi-page-view-menu-new.png)
* 在 [編輯] 檢視中您會看到這個項目。
  
    ![](media/power-bi-change-report-display-settings/power-bi-view-editing-view.png)

1. 讓我們使用 [實際大小] 設定來看看頁面外觀吧。
   
   ![](media/power-bi-change-report-display-settings/power-bi-actal-size2.png)
   
   不太好，儀表板現在有雙重捲軸。
2. 請切換至 [調整成視窗寬度] 。
   
   ![](media/power-bi-change-report-display-settings/pbi_fit_to_width.png)
   
   看起來好一點，我們現在有了捲軸，但比較容易閱讀詳細資料。

## <a name="change-the-default-view-for-a-report-page"></a>變更報表頁面的預設檢視
所有 Power BI 報表皆預設為 [符合一頁大小] 檢視。 但如果您想要一律以 [實際大小] 檢視開啟此報表頁面怎麼辦？

1. 在報表的 \[New stores] \(新商店) 頁面中，切換回 [實際大小] 檢視。
   
   ![](media/power-bi-change-report-display-settings/power-bi-actual-size.png)
2. 選取 [檔案] > [另存新檔]，將報表儲存為不同名稱。 您現在有 2 份此報表。在原始報表中，\[New stores] \(新商店) 會繼續在預設檢視中開啟，但在新報表中會以 [實際大小] 檢視開啟。 讓我們看看。
   
   ![](media/power-bi-change-report-display-settings/power-bi-save-as.png)
3. 從上方導覽列選取目前工作區的名稱，返回該工作區。  
   
   ![](media/power-bi-change-report-display-settings/power-bi-my-workspace.png)
4. 選取 [報表] 索引標籤，然後選擇您剛建立的新報表 (會有黃色星號)。
   
    ![](media/power-bi-change-report-display-settings/power-bi-new-report2.png)
5. 報表會在 [實際大小] 檢視中開啟！
   
   ![](media/power-bi-change-report-display-settings/power-bi-actal-size2.png)

## <a name="now-lets-explore-the-page-size-setting"></a>現在讓我們來探索 [頁面大小] 設定
只有[編輯檢視](service-interact-with-a-report-in-editing-view.md)才能使用頁面大小設定。 若要以編輯檢視開啟報表，您必須具有報表的擁有者權限。 如果您已連接到任何[範例](sample-datasets.md)，則會具有這些報表的擁有者權限。

1. 在 [編輯檢視] 中開啟[零售分析範例](sample-retail-analysis.md)的「區域每月銷售額」頁面。
2. 請確定在畫布上未選取任何視覺效果。  在 [視覺效果] 窗格中，選取油漆滾筒圖示 ![](media/power-bi-change-report-display-settings/power-bi-paintroller.png)。
3. 選取 [頁面大小] &gt; [類型] 以顯示頁面大小選項。
   
   ![](media/power-bi-change-report-display-settings/power-bi-page-size-menu-new.png)
4. 選取 [信件] 。  在畫布的白色部分上，只能保留可容納在 816 x 1056 像素 (信件大小) 的內容。
   
   ![](media/power-bi-change-report-display-settings/power-bi-letter-new.png)
5. 如果我們將 [檢視]  變更為「調整成視窗寬度」，則我們的畫布現在只顯示能符合信件大小的頁面內容。
   
   ![](media/power-bi-change-report-display-settings/power-bi-fit-to-width-new.png)
6. 選取 [頁面大小]，[16:9] 比率。
   
   ![](media/power-bi-change-report-display-settings/power-bi-16-to-9-new.png)
   
   報表頁面會使用寬度 16、高度 9 的比例顯示。 若要查看所使用的實際像素大小，請看一下灰色的寬度和高度欄位 (1280 x 720)。 報表畫布周圍有很多空白空間，這是因為我們先前將 [檢視] 設定為 [符合一頁大小]。
7. 繼續探索 [頁面大小] 選項。

## <a name="using-page-view-and-page-size-together"></a>同時使用 [頁面檢視] 和 [頁面大小]
同時使用 [頁面檢視] 和 [頁面大小]，來建立在內嵌於另一個應用程式時顯示效果最好的報表。

在此練習中，您將建立報表頁面，它會顯示在擁有 500 像素寬、750 個像素高之空間的應用程式中。

請記住，在上一個步驟中，我們看到報表頁面目前顯示為 1280 寬、720 高。 因此我們知道，如果我們想要所有視覺效果都符合，就需要進行大量的調整大小和重新排列。

1. 調整大小並移動視覺效果，使其可以放在小於目前畫布區域一半的空間。
   
    ![](media/power-bi-change-report-display-settings/power-bi-custom-view.gif)
2. 選取 [頁面大小] &gt; [自訂]。
3. 請將寬度設為 500 ，並將高度設為 750。
   
    ![](media/power-bi-change-report-display-settings/power-bi-custom-new.png)
4. 調整 [報表] 頁面，使顯示效果達到最佳。 切換 [檢視] > [實際大小] 和 [檢視] > [符合一頁大小] 進行調整。
   
    ![](media/power-bi-change-report-display-settings/power-bi-final-new.png)

## <a name="next-steps"></a>後續步驟
[建立 Cortana 的報表](service-cortana-answer-cards.md)

回到 [Power BI 報表的頁面顯示設定](power-bi-report-display-settings.md)

深入了解 [Power BI 中的報表](service-reports.md)

有其他問題嗎？ [試試 Power BI 社群](http://community.powerbi.com/)

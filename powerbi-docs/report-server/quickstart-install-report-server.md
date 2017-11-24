---
title: "快速入門︰安裝 Power BI 報表伺服器"
description: "安裝 Power BI 報表伺服器本身非常快速。 無論是下載還是安裝及設定，您應都可在幾分鐘內即啟動並執行。"
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
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 06/28/2017
ms.author: asaxton
ms.openlocfilehash: 2e616369333d3bb2747ec20eb2072b69d5b9f9d5
ms.sourcegitcommit: 99cc3b9cb615c2957dde6ca908a51238f129cebb
ms.translationtype: HT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/13/2017
---
# <a name="quickstart-install-power-bi-report-server"></a>快速入門︰安裝 Power BI 報表伺服器
安裝 Power BI 報表伺服器本身非常快速。 無論是下載還是安裝及設定，您應都可在幾分鐘內即啟動並執行。

若您僅想使用新伺服器進行啟動並執行，此為安裝報表伺服器的概觀。 如需有關安裝報表伺服器的詳細資訊，請參閱[安裝 Power BI 報表伺服器](install-report-server.md)。

 **下載**![下載](media/quickstart-install-report-server/download.png "下載")

若要下載 Power BI 報表伺服器，請移至[使用 Power BI 報表伺服器的內部部署報表](https://powerbi.microsoft.com/report-server/)。 若要下載針對 Power BI 報表伺服器最佳化的 Power BI Desktop，請移至 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=837581)。

![提示](media/quickstart-install-report-server/fyi-tip.png "提示")如需目前的版本資訊，請參閱 [Power BI 報表伺服器版本資訊](release-notes.md)。

<iframe width="640" height="360" src="https://www.youtube.com/embed/zacaEb9A4F0?showinfo=0" frameborder="0" allowfullscreen></iframe>

## <a name="before-you-begin"></a>開始之前
安裝 Power BI 報表伺服器之前，建議您先檢閱[安裝 Power BI 報表伺服器的硬體和軟體需求](system-requirements.md)。

## <a name="step-1-download"></a>步驟 1︰下載
在本機下載 Power BI 報表伺服器的安裝檔案。 若要下載 Power BI 報表伺服器，請移至 [Microsoft 下載中心](https://go.microsoft.com/fwlink/?linkid=839351)。

![下載 Power BI 報表伺服器](media/quickstart-install-report-server/download-pbireportserver.png)

## <a name="step-2-run-installer"></a>步驟 2︰執行安裝程式
執行您所下載的 PowerBIReportServer.exe 檔案，並逐步執行安裝畫面。 您會有機會選擇安裝路徑，以及您想要安裝的版本。 您可以選擇 180 天後會到期的評估版、開發人員版本，或是提供產品金鑰。

![安裝 Power BI 報表伺服器](media/quickstart-install-report-server/pbireportserver-install.png)

## <a name="step-3-configure-the-server"></a>步驟 3︰設定伺服器
完成安裝後，您將執行組態管理員來完成設定您的伺服器。 您會需要建立 ReportServer 目錄資料庫，以及確認入口網站和 Web 服務 URL。

![設定 Power BI 報表伺服器](media/quickstart-install-report-server/pbireportserver-configure.png)

## <a name="step-4-browse-to-web-portal"></a>步驟 4︰瀏覽至入口網站
現在您已設定好，便應能夠開啟瀏覽器連至您伺服器的入口網站。 根據預設，這會是 `http://localhost/reports`。 假設任何類型的防火牆皆未封鎖您，您便也能夠使用電腦名稱進行瀏覽，而無須依預設使用 localhost。

![Power BI 報表伺服器入口網站](media/quickstart-install-report-server/web-portal.png)

## <a name="next-steps"></a>後續步驟
[系統管理員手冊](admin-handbook-overview.md)  
[如何找到您的報表伺服器產品金鑰](find-product-key.md)  
[安裝 Power BI 報表伺服器](install-report-server.md)  
[安裝針對 Power BI 報表伺服器最佳化的 Power BI Desktop](install-powerbi-desktop.md)  
[Power BI 報表伺服器的瀏覽器支援](browser-support.md)

有其他問題嗎？ [嘗試在 Power BI 社群提問](https://community.powerbi.com/)

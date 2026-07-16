[English](README.md) | **繁體中文**

# Chao Chien Wang｜資料分析・商業分析

資料分析／商業分析工作者，具製造、供應鏈與財務風險管理實務。能從使用者需求釐清與作業流程理解出發，運用 Python、SQL、Power BI 及 Power Platform 完成跨系統資料整合、流程自動化與管理報表。代表成果包括每月處理約 **1.5 億美元**外匯風險，以及支援超過 **50 種原料、每月約新台幣 10 億元**成本規模的管理系統。

## 核心能力

- **業務分析：** 使用者需求釐清、指標與規則定義、流程理解、跨部門協作
- **資料分析：** Python、SQL、資料清理、資料建模
- **視覺化與自動化：** Power BI、Power Automate、Power Apps
- **領域經驗：** 製造、原料供應鏈、成本控制、外匯風險

## 精選專案

### 1. [BOM 智慧運算與管理平台](https://github.com/ChienChienChien/BOM_Management_Platform)

整合 BOM 參數、運算、版本及發布流程，保留每次運算的輸入條件與結果，提升作業穩定性及可追溯性。

- BOM1 每週更新；BOM2 由現場即時觸發
- 串接參數管理、簽核、驗證、發布與下游應用
- 2023 年底上線，持續維運與改版

### 2. [原料進耗存預測與庫存告警系統](https://github.com/ChienChienChien/Material_Forecasting_System)

整合庫存、採購、BOM 與生產計畫，逐日推估未來三個月庫存，提前辨識缺料風險。

- 管理超過 **50 種原料**，每月成本規模約 **新台幣 10 億元**
- 以 Power BI 呈現庫存趨勢、風險清單及日別明細
- 透過 Teams 每日推送分級告警

### 3. [製造資料品質監控平台](https://github.com/ChienChienChien/Manufacturing_Data_Quality_Monitoring)

每日檢查 BOM 使用的關鍵資料表，在運算前辨識空表、欄位缺漏及更新延遲。

- 監控 **8 張關鍵資料表**
- 以 Power BI 呈現結果，異常由 Power Automate 推送至 Teams
- 曾於運算前發現空表並協助排除；資料改接 MES 後逐步退場

### 4. [外匯風險自動拋轉系統](https://github.com/ChienChienChien/FX_Hedging_Automation)

整合銷售、採購、發票與匯率資料，依合約異動及立帳結果，自動建立、調整與結清外匯部位。

- 每月處理約 **1.5 億美元**外匯風險
- 統一跨部門風險認定、匯率及結清規則
- 釐清使用者與作業需求、定義規則、整合資料並開發流程

---

本作品集僅呈現去識別化的專案說明與架構，不含公司原始資料、連線資訊及未處理的內部程式碼。

# taiwan-invoice-to-excel-excel-
台灣發票批次轉 Excel 智慧工具 - 支援電子發票離線處理與手寫發票 AI 破解
# 🇹🇼 台灣發票批次轉 Excel 智慧工具 (Taiwan Invoice to Excel Converter)

專為台灣會計人員、中小企業、網拍賣家打造的 **「離線高速 + AI 雲端手寫備援」** 桌面小工具。
解決每到報稅季，面對大量傳統二聯式手寫發票、收銀機統一發票、三聯式 PDF 需要人工Key入 Excel 的地獄級痛點！

[![GitHub release](https://img.shields.io/github/v/release/你的帳戶名稱/你的倉庫名稱?include_prereleases&style=flat-square)](https://github.com/你的帳戶名稱/你的倉庫名稱/releases)
[![Buy Me A Coffee](https://img.shields.io/badge/Support-Buy%20Me%20A%20Coffee-%23FF5722?style=flat-square&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/你的贊助連結)

---

## ✨ 核心功能特色

1. **⚡ 智慧分流機制（安全與速度兼具）**
   - **電子發票 / 數位 PDF**：直接由本機高速離線解析（100%免費、秒殺處理、絕不上傳任何個資）。
   - **手寫發票 / 傳統掃描檔**：自動辨識無內文頁面，透過免費 Gemini API 進行智慧視覺與會計邏輯破解。
2. **🧮 內建台灣在地稅務邏輯**
   - 自動抓取 8 碼統一編號、發票字軌號碼、買賣雙方統編。
   - 支援**二聯式發票 5% 營業稅反推未稅金額與稅額計算**。
   - 支援三聯式發票明確欄位對應。
3. **🛡️ 中途停止保護系統**
   - 批次處理幾百張發票時，隨時可以點擊「停止並匯出」，程式會立刻將目前已完成的進度整理成 Excel 報表安全導出到桌面。
4. **⏳ 免費額度冷卻防護**
   - 內建 AI 請求間隔保護，完美對應 Google AI Studio 免費層級（Free Tier），絕不因瞬間流量過大而噴發 429 錯誤。

---

## 📥 如何下載與使用 (免安裝 `.exe`)

1. 前往本專案的 [Releases 頁面](../../releases) 下載最新的壓縮檔 (`.zip`)。
2. 解壓縮後，雙擊執行 `invoice_to_excel_gui.exe` 即可直接使用！
3. **（選填）若要解鎖手寫發票 AI 破解**：
   - 點擊介面上的「免費取得金鑰 ↗」前往 Google AI Studio 申請一組免費的 Gemini API Key。
   - 將金鑰貼入輸入框中即可（程式會自動記憶）。

---

## 🔒 隱私與安全性聲明
- 本程式為 100% 開源專案，所有原始碼皆可檢視。
- 您的帳務發票資料僅在您的電腦本機運作；若使用 AI 手寫備援，也僅透過您自己的 API Key 點對點傳輸至 Google 官方伺服器，作者絕不經手或收集任何個資。

---


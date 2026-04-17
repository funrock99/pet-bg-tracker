# 🐾 Pet BG Tracker - 前端網頁

本儲存庫包含「寵物血糖紀錄系統」的前端組件，主要用於 LINE 整合與數據視覺化。

## 📁 檔案說明
- **`form.html`**：LIFF (LINE Front-end Framework) 網頁表單，提供使用者在 LINE App 內一次性填寫血糖、胰島素與餵食量。
- **`index.html`**：數據視覺化儀表板，透過 Chart.js 串接 GAS API 並顯示 Notion 資料庫中的血糖波動趨勢。

## 🚀 主要功能
- **數據視覺化**：透過 `index.html` 即時展示血糖趨勢。
    - **多寵物切換**：支援管理多隻寵物的數據。
    - **日期區間查詢**：支援依日期範圍過濾歷史紀錄，預設顯示最近 30 天。
- **快速紀錄**：透過 `form.html` (LIFF) 在 LINE 內快速填寫數據。

---
本專案與 Google Apps Script (GAS) 後端及 Notion API 協同運作。

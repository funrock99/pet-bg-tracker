# 🐾 Pet BG Tracker - 前端網頁

本儲存庫包含「寵物血糖紀錄系統」的前端組件，主要用於 LINE 整合與數據視覺化。

## 📁 檔案說明
- **`form.html`**：LIFF (LINE Front-end Framework) 網頁表單，提供使用者在 LINE App 內一次性填寫血糖、胰島素與餵食量。
- **`index.html`**：數據視覺化儀表板，透過 Chart.js 串接 GAS API 並顯示 Notion 資料庫中的血糖波動趨勢。

## 🚀 部署建議
- 本目錄適合部署於 **GitHub Pages** 以提供靜態網頁存取。
- `index.html` 存取時需帶入 `?key=您的金鑰` 以通過安全驗證。

---
本專案與 Google Apps Script (GAS) 後端及 Notion API 協同運作。

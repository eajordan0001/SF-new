# 超鈒 Super Fan 配送助手 PWA 開發包

這是一個專門為了超鈒配送司機設計的輕量級 Web 應用程式 (PWA)。

## 📁 檔案清單說明
1. `index.html`：主程式網頁（包含骨架、超鈒品牌青藍配色 CSS、以及搜尋/過濾大腦 JS）。
2. `manifest.json`：PWA 設定檔，定義 App 於手機桌面的名稱、主題色及 PNG 圖示路徑。
3. `sw.js`：Service Worker 腳本，負責處理手機端的快取檔案，提供優質的載入體驗。
4. `icon-192.png` / `icon-512.png`：轉換後符合 PWA 嚴格規範的官方圖示。

## 🚀 5 分鐘 GitHub 快速部署指南

1. **解壓縮開發包**：將此壓縮檔解壓縮至您的電腦中。
2. **修改網址**：用記事本開啟 `index.html`，尋找 `YOUR_GAS_URL` 字樣，將其替換為您從 Google 試算表發布的 Apps Script 網頁應用程式網址，然後儲存。
3. **上傳至 GitHub**：
   - 登入 GitHub，建立一個全新的公開倉庫 (Repository)，命名為 `driver-app`。
   - 將解壓後的所有檔案（共 5 個檔案）一併拖曳上傳至該倉庫的根目錄。
4. **啟用 GitHub Pages**：
   - 在您的 GitHub 倉庫頁面，點擊右上角的 **Settings** (設定)。
   - 在左側選單點選 **Pages**。
   - 在 Build and deployment 區塊下的 Branch，將 `None` 改選為 `main` (或 `master`)，並點擊 **Save**。
5. **在手機上安裝 App**：
   - 稍等約 1 分鐘後重新整理 Pages 頁面，會獲得一組專屬網址（例如：`https://您的帳號.github.io/driver-app/`）。
   - 用手機瀏覽器打開該網址：
     - **Android (Chrome)**：點擊瀏覽器選單，選擇「**新增至主畫面**」或「**安裝應用程式**」。
     - **iPhone (Safari)**：點擊底部的「**分享**」按鈕，向下捲動並選擇「**加入主畫面**」。
   - 手機桌面即會出現帶有「超鈒 SF 地球標誌」的專屬獨立 App！

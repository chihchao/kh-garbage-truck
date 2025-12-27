# 🚚 高雄市垃圾車即時定位 (Kaohsiung Garbage Truck Tracker)

[🚚 高雄市垃圾車即時定位](https://chihchao.github.io/kh-garbage-truck/)

這是一個基於 web 的輕量級應用程式，用於即時顯示高雄市垃圾車的位置。
資料來源使用 [高雄市政府資料開放平台](https://data.kcg.gov.tw/) 的即時 API。

## 🌟 功能特色

*   **即時定位**：顯示高雄市目前執勤中的垃圾車位置。
*   **使用者定位**：可點擊按鈕快速定位使用者目前所在位置（需授權）。
*   **自動更新**：每 60 秒自動重新抓取最新資料。
*   **響應式設計**：支援手機與電腦瀏覽，滿版地圖體驗。

## 🚀 如何使用 (GitHub Pages)

本專案已最佳化，適合直接部署於 GitHub Pages。

1.  進入 Repo 的 **Settings** > **Pages**。
2.  在 **Branch** 選擇 `main` 並儲存。
3.  等待約 1-2 分鐘，GitHub 會提供一組 HTTPS 網址（例如：`https://your-username.github.io/kh-garbage-truck/`）。
4.  開啟該網址即可使用。

> **注意**：由於瀏覽器安全性限制，**地理定位功能 (Geolocation)** 必須在 **HTTPS** 環境下才能正常運作。GitHub Pages 預設提供 HTTPS，因此是執行的最佳環境。

## 🛠️ 技術棧

*   **HTML5 / JavaScript (ES6+)**
*   **Leaflet.js** - 用於地圖繪製 (OpenStreetMap)
*   **Tailwind CSS** - 用於 UI 樣式設計 (CDN 版本)

## ⚠️ 常見問題

**Q: 為什麼顯示「定位失敗：使用者拒絕提供位置」？**
A: 請確認：
1. 您是否在彈出視窗中點擊了「允許」？
2. 您的裝置是否有開啟 GPS/定位功能？
3. 如果是在本地端開發，請使用 `localhost` 或 `https` 協定開啟。



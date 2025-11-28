🇹🇭 My Tour - 泰國旅遊規劃 Web App 2.0

這是一個基於 Vue.js 3 與 Tailwind CSS 開發的單頁式旅遊規劃應用程式 (SPA)。
版本 2.0 整合了 Google Gemini AI 與 Firebase Firestore，實現了智慧行程建議與多人即時協作功能。

✨ 2.0 版本新功能

🤖 AI 智慧賦能 (Powered by Gemini)

AI 行程健檢：一鍵分析當日行程順暢度，提供優化建議與缺漏提醒。

AI 智慧匯入：直接貼上文字版行程（如 Line 對話紀錄），AI 自動解析並轉換為結構化行程卡片。

景點智慧建議：自動抓取景點的天氣資訊與穿著建議。

☁️ 雲端協作 (Firebase)

即時同步：所有行程與成員更動皆即時同步至雲端資料庫。

多人留言板：針對每個行程項目，成員可以發表留言與討論。

成員管理：支援管理員 (Admin) 與一般成員權限控管。

🎨 UI/UX 優化

液態玻璃擬態風格：精美的 Morandi 色系與磨砂玻璃質感。

RWD 響應式設計：完美支援手機與電腦版面。

Google 地圖預覽：行程編輯時可直接預覽地點位置。

🚀 如何使用

本專案為單一 HTML 檔案架構，無需安裝 Node.js 或編譯。

下載 index.html (原 ThailandTripPlanner.html)。

直接用瀏覽器 (Chrome/Safari) 開啟即可使用。

若要啟用 AI 與 資料庫功能，請確保網路連線正常。

🛠️ 技術堆疊

Frontend: Vue.js 3 (Composition API), Tailwind CSS

Backend (BaaS): Google Firebase (Auth, Firestore)

AI Model: Google Gemini 2.5 Flash

Map: Google Maps Embed API

Weather: Open-Meteo API

📝 版本紀錄

v2.0: 新增 AI 匯入、AI 健檢、Firebase 真實資料庫連結、UI 大改版。

v1.0: 基礎行程 CRUD、本地暫存。

Developed with ❤️ for Thailand Trip
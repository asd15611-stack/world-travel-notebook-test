# 世界旅記 V2.2｜獨立 PWA 測試站

本儲存庫僅用於《世界旅記》測試，與《越南冒險日記》完全獨立。

## 使用與部署

GitHub → Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。

發佈後測試網址： https://asd15611-stack.github.io/world-travel-notebook-test/

**目前是候選測試版，不是正式穩定版。** 必須另行在手機確認 HTTPS 開啟、安裝、首次連網後飛航模式重開、重新整理與本機資料保留。

## 資料安全

資料儲存於目前網址的瀏覽器本機空間。網站來源與本機 HTML 並不共用資料；初次開啟新網址不會自動帶入舊版記帳、行程等內容。

建議先從舊版匯出 JSON 備份，並依 APP 的安全匯入流程建立複本。請勿把含個人或護照資訊的備份直接提交至公開儲存庫。

## 內容

- index.html：主要介面與資料處理
- manifest.webmanifest：安裝描述
- service-worker.js：離線快取
- icon.svg、icons/：APP 圖示


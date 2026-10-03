# GA4 多頁 GitHub Pages 測試站

這是一個部署在 GitHub Pages 的多頁網站，用來測試 Google Analytics 4 (GA4) 的基本追蹤、自訂事件、表單事件、外部連結點擊與捲動深度追蹤。

## 網站功能
- 首頁 / 關於頁 / 聯絡頁
- GA4 page_view 追蹤
- 自訂點擊事件
- 表單送出事件
- 外部連結點擊事件
- 捲動深度事件
- 導覽列點擊事件

## 測試事件
- `page_view`
- `home_button_click`
- `about_click`
- `contact_form_submit`
- `outbound_click`
- `scroll_depth`
- `nav_click`

## 網站結構
- `index.html`
- `about.html`
- `contact.html`
- `styles.css`

## 部署方式
1. 將專案上傳到 GitHub repository
2. 到 `Settings > Pages`
3. 選擇 `Deploy from a branch`
4. Branch 選 `main`
5. Folder 選 `/root`
6. 儲存並等待部署完成

## GA4 設定
每個頁面都已載入 GA4 gtag.js，並使用相同的 Measurement ID。
可在 GA4 的 Realtime 與 DebugView 中檢查事件。

## 展示重點
- 證明多頁網站可正常部署
- 證明 GA4 可追蹤頁面瀏覽
- 證明可送出自訂事件與參數
- 證明可觀察互動行為與用戶操作





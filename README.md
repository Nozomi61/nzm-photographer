# 攝影師作品集網站

以繁體中文呈現的蔡孟辰／NZM Photographer 多頁網站，主打 Cosplay、人像與活動紀錄攝影。包含首頁、作品集、個人履歷、收費方式、互惠合作和聯絡頁，使用原生 HTML、CSS 與 JavaScript，無需安裝相依套件、外部字型或建置工具。

## 開啟方式

直接在瀏覽器開啟 `index.html` 即可預覽，也可以使用 VS Code 的 Live Server 等靜態檔案伺服器。
導覽列會切換到 `portfolio.html`、`resume.html`、`pricing.html`、`collaboration.html` 和 `contact.html` 等獨立頁面。

## 個人化內容

- 更新攝影介紹、作品分類、專案名稱與說明。
- 履歷頁的攝影器材型號可在 `resume.html` 的「攝影器材」欄位填入；服務期間、合作單位與學歷也請依實際資料確認。可使用「列印 / 另存 PDF」輸出。
- 聯絡區已設定蔡孟辰提供的電子郵件與電話；如需變更，請編輯 `index.html` 的聯絡區。
- Instagram 連至 `@ykacgn17_t0kisaki`；Facebook 連至 NZM Photographer 個人頁。
- 首頁和作品集目前使用 `images/01cosplay.jpg`、`images/02portralt.jpg`、`images/03event.jpg`；互惠合作頁使用 `images/04collaboration.jpg`。更換照片時，更新 `styles.css` 的 `:root` 中對應圖片變數即可。

## 技術

- HTML、CSS、原生 JavaScript
- 字型使用系統字型，離線時仍可正常瀏覽。
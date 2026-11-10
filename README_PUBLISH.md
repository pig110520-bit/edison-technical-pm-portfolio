# Edison Portfolio　完整修復

## 出現頁面打不開、圖片不顯示的原因
「僅更新 5 個檔案」不是完整網站，其中多個頁面引用 `assets/screenshots/`、`assets/automation-evidence/` 等子目錄。如果曾只上傳更新包或上傳時失去子資料夾階層，頁面會缺圖片或樣式。本完整修復包已包含所有網頁、CSS、圖檔、PDF 及健康檢查頁。

## 上傳前確認
- **請解壓縮 ZIP，再將解壓縮後的內容上傳到 GitHub Repository 的根目錄（main 分支）。**
- GitHub 根目錄需直接看到 `index.html`、`styles.css`、`resume.html`、`site-check.html`、`assets/`、`projects/`。
- **不能把 ZIP 本身上傳，也不能多套一層 `Edison_Portfolio_V20_Complete_Repair` 目錄。**
- `projects` 資料夾需要有四個 HTML，`assets` 裡需包含 `screenshots/` 與 `automation-evidence/`。
- 為避免遺漏資料夾，建議從 Windows 檔案總管**一次拖曳解壓縮後的所有檔案及資料夾**到 GitHub 的 Upload files 畫面；確認檔案清單包含 `assets/screenshots/dashboard.webp` 等路徑，再 Commit。

## 發布後檢查
打開 `https://pig110520-bit.github.io/edison-technical-pm-portfolio/site-check.html`，檢查是否全部正常。
請另外測試四個專頁以及手機版排版。若出現「缺少」請截圖健康檢查頁。

## 注意
已保留原先作品集敘述與素材，僅將版本打包成完整可上傳站點並加上健康檢查頁。不保證已能讀取目前 GitHub 的遠端實際檔案；若站點仍錯，需查看 GitHub Repository 的實際資料夾位置。

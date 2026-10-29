# 減重日誌小幫手

## 重要：請用 Safari 或已部署的網站開啟
如果在 ChatGPT 內建預覽中按鈕完全沒反應，通常是預覽環境沒有執行這個 HTML 檔案的 JavaScript，不是表單內容有問題。

## 部署成可正常使用的網址（GitHub Pages）
1. 登入 GitHub，建立一個新的 repository（例如 `weight-diary`）。
2. 將 `index.html` 上傳到 repository 根目錄。
3. 進入 repository 的 Settings → Pages。
4. 在 Build and deployment 選擇 Deploy from a branch。
5. Branch 選 `main`，資料夾選 `/ (root)`，按 Save。
6. 等待部署完成後，使用 GitHub Pages 顯示的網址開啟。
7. 在 iPhone Safari 開啟該網址即可填寫和儲存。

## 資料注意事項
- 紀錄儲存在目前瀏覽器的 localStorage。
- 清除 Safari 網站資料或更換裝置可能會遺失紀錄，請定期匯出 CSV。
- 這個小工具不會自動傳送資料到 ChatGPT。

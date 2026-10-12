# trip-images

日本行程網站使用的公開圖片庫，由 Google Apps Script 網站透過 HTTPS 載入圖片。此 Repo 不需要啟用 GitHub Pages。

## 使用方式

圖片放在 `images/`。網站正式版本使用固定 commit 的原始檔網址，避免圖片更新影響既有版本：

```text
https://raw.githubusercontent.com/Edgar0119/trip-images/<commit>/images/<filename>
```

更新圖片後，需同步更新網站使用的 commit，並驗證圖片可正常載入。

本圖片庫為公開儲存庫，請勿上傳私人訂單、付款憑證、存取金鑰或其他不宜公開的內容。

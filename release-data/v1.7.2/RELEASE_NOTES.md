# PixG v1.7.2

PixG v1.7.2 是目前的最小權限發布版，適合從 GitHub 下載測試或手動安裝。

## 主要更新

- 權限縮減為 `downloads`、`storage`。
- 網站存取限制為 `https://chatgpt.com/*` 與 `https://*.oaiusercontent.com/*`。
- 移除右鍵選單與 `contextMenus` 權限。
- 保留 Web ChatGPT 尺寸輔助、圖片擷取與精準輸出流程。
- 支援 Cover / Contain / Stretch、九宮格與手動裁切。
- 支援透明畫布、自動去空白、PNG / JPEG / WebP。
- 下載前重新驗證實際像素與格式。
- 支援自訂下載檔名。

## 一般使用者

請下載 **`PixG-v1.7.2-store.zip`**。

解壓縮後：

1. Chrome 開啟 `chrome://extensions/`
2. 開啟「開發人員模式」
3. 點「載入未封裝項目」
4. 選擇解壓後、含 `manifest.json` 的資料夾
5. 重新整理 `https://chatgpt.com/`

> 這是 GitHub 手動安裝方式；正式一般使用者建議優先使用 Chrome Web Store。

## 開發者

`PixG-v1.7.2-source.zip` 包含擴充功能程式碼與發布文件。

## 校驗

Release 同時附上兩個 `.sha256` 檔，可用來驗證下載檔案完整性。

- Product: https://index7777.github.io/PixGauge/
- Privacy: https://index7777.github.io/PixGauge/privacy.html
- Support: https://github.com/index7777/PixGauge/issues

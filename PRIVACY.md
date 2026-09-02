# PixG 隱私權政策

最後更新：2026-09-02

PixG（像素G）是一個在瀏覽器本機運作的 Chrome 擴充功能，用於協助 Web ChatGPT 圖片生成的尺寸提示，以及圖片裁切、縮放、格式轉換與下載。

正式公開網址：

- https://index7777.github.io/PixGauge/privacy.html

## 資料處理

PixG 不經營自有後端服務，也不會把圖片、提示詞或轉換後檔案傳送到 PixG 的伺服器。

擴充功能會在使用者操作時讀取目前 ChatGPT 頁面中的必要 DOM 資訊，以便：

- 找到 ChatGPT 輸入框並填入使用者要求的尺寸輔助文字。
- 偵測新生成的圖片。
- 取得使用者明確選擇進行精準輸出的圖片來源。

PixG 會使用 `chrome.storage.local` 在使用者裝置本機保存或暫存：

- PixG 浮動按鈕位置。
- 等待開啟編輯器的單次圖片來源 URL。
- 該次工作流的目標寬度與高度。

這些資料不會由 PixG 開發者遠端收集。

## 圖片處理

裁切、縮放、Canvas 繪製、PNG / JPEG / WebP 編碼與尺寸驗證均在使用者瀏覽器本機完成。

若 ChatGPT 圖片來源允許，PixG 可能從 ChatGPT / OpenAI 的圖片來源網址讀取圖片；若來源受到登入、簽名 URL 或其他存取控制限制，PixG 不會繞過限制，使用者可改用貼上、拖曳或本機選檔。

## 第三方服務

使用 Web ChatGPT 時，使用者與 OpenAI 之間的資料處理受 OpenAI 自身條款與隱私政策約束。PixG 不代表 OpenAI，亦非 OpenAI 官方產品。

## 資料出售、廣告與追蹤

PixG 不出售使用者資料、不使用使用者資料投放廣告，也不加入第三方分析或追蹤 SDK。

## 聯絡方式

如有隱私權或產品問題，可透過公開 GitHub Issues 聯絡維護者：

- https://github.com/index7777/PixGauge/issues

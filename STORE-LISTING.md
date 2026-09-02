# PixG Chrome Web Store 上架資料

## 名稱

像素G PixG｜AI 圖片精準輸出

## 短名稱

PixG

## 短摘要

讓 Web ChatGPT 圖片依目標比例生成，並在瀏覽器本機裁切、縮放、驗證與輸出真正指定的像素尺寸。

## 完整說明

ChatGPT 生圖提示中的 800×600、1920×1080 等尺寸，不一定等於最後圖片檔案的真正像素尺寸。PixG 將「生成比例」與「精準像素輸出」拆成兩個步驟：先保留你原本的圖片提示詞，只輔助 ChatGPT 使用適合的畫面比例；圖片生成後，再在瀏覽器本機完成裁切、縮放、格式轉換與尺寸驗證。

主要功能：

- 只解析目標寬高與比例，不改寫圖片內容需求。
- ChatGPT 圖片 hover 一鍵開啟精準輸出。
- 單一所見即所得預覽區。
- Cover / Contain / Stretch。
- 九宮格裁切位置與可拖曳手動裁切。
- 自動去除透明或純色空白邊界。
- 可調整預覽畫布顏色，方便辨認透明區與畫布尺寸。
- PNG / JPEG / WebP 輸出。
- 下載前重新驗證真正像素尺寸與格式。
- 圖片處理在本機完成，不需要 OpenAI API Key。

PixG 非 OpenAI 官方產品。

## 單一用途（Single purpose）

協助 Web ChatGPT 圖片依使用者指定的尺寸比例生成，並將生成圖片在本機轉換為精確指定的像素尺寸與格式。

## 權限用途

- `contextMenus`：在 ChatGPT 圖片右鍵選單提供「用像素G精準輸出」。
- `downloads`：下載本機轉換並驗證完成的圖片。
- `storage`：僅在本機保存浮動按鈕位置及單次圖片／尺寸工作流資訊。
- `tabs`：從工具列、ChatGPT 圖片或產品資訊入口開啟 PixG 頁面。
- `chatgpt.com` host permission：注入 PixG 尺寸輔助與圖片精準輸出介面。
- `oaiusercontent.com` / `openai.com` host permission：在來源允許時讀取使用者已可存取的 ChatGPT 圖片。

## Store / Privacy URLs

- Product / Listing URL：`https://index7777.github.io/PixGauge/`
- Privacy Policy URL：`https://index7777.github.io/PixGauge/privacy.html`
- Support URL：`https://github.com/index7777/PixGauge/issues`
- Source / Repository：`https://github.com/index7777/PixGauge`

## Privacy Dashboard 建議聲明

- 不出售資料。
- 不將資料用於與擴充功能單一用途無關的目的。
- 不使用遠端程式碼。
- 不加入第三方分析或追蹤 SDK。
- 圖片轉換在本機完成。

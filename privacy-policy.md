# Privacy Policy Draft（隱私權政策草稿）

## 1. 產品資訊
本擴充功能名稱為 **WebKB - Local Knowledge Clipper**。

## 2. 收集與儲存的資料
WebKB 僅處理使用者主動保存的內容，可能包含：
- 網頁標題
- 原始網址
- 作者 / 網站名稱
- 摘要
- 正文內容
- 分類
- 標籤
- AI 摘要
- AI Provider 設定
- 使用者自行輸入的 AI API Key

## 3. 資料存放位置
- 使用者本機下載資料夾下的 `WebKnowledgeBase`
- 瀏覽器 `chrome.storage.local`

## 4. AI 資料傳輸
- 僅在使用者主動點擊「AI 建議」時，才會傳送文章標題、摘要與部分正文到使用者選定的 AI Provider。
- 支援：DeepSeek / Gemini / OpenAI / Custom OpenAI-compatible。
- Chrome Built-in AI 若可用，會在瀏覽器本機環境處理。
- 開發者不接收、不代理、不儲存 AI 請求內容。

## 5. API Key 處理
- API Key 僅儲存在使用者本機 `chrome.storage.local`。
- API Key 不會寫入文章輸出檔（`article.html`、`article.md`、`metadata.json`、`index.html`、`articles.csv`）。
- API Key 不會上傳到開發者伺服器。
- 使用者可自行刪除或更換 API Key。

## 6. 開發者聲明
- 不販售使用者資料。
- 不與資料仲介共享資料。
- 不建立追蹤使用者瀏覽紀錄的伺服器資料庫。
- 不使用遠端程式碼（remote code）。

## 7. 使用者控制
- 可在 Library 軟刪除文章紀錄。
- 可手動刪除本機 `WebKnowledgeBase` 資料夾。
- 可移除 extension。
- 可清除瀏覽器 extension storage。

## 8. 聯絡方式
- amigo@ctcn.edu.tw
- dallmeyer99@gmail.com

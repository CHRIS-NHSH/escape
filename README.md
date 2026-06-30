# escape — 機關範例庫

校園密室／闖關活動用的互動機關範例庫。首頁彙整各式機關，每個機關是獨立的單檔網頁，可直接在平板操作。

## 結構
- `index.html` — 首頁（範例庫；長按右上角齒輪進首頁後台可新增／修改／刪除機關、設定程式碼分享）
- `lock/index.html` — 機關 No.01：密碼鎖
- `morse/index.html` — 機關 No.02：摩斯密碼燈
- `puzzle/index.html` — 機關 No.03：線索拼圖
- `cards/index.html` — 機關 No.04：翻牌記憶
- `wires/index.html` — 機關 No.05：連線謎題
- `uv/index.html` — 機關 No.06：紫外線顯影
- `bomb/index.html` — 機關 No.07：拆炸彈

## 各機關
每個機關都有自己的後台（長按右上角齒輪 → 輸入後台密碼，預設 `1234`）可修改內容。

## 範本
- `template/index.html` — 空白機關起手骨架（共用外殼已備好，找 `✏️` 標記填入玩法）

## 新增機關
1. 在 `<名稱>/index.html` 放該機關的單檔網頁。
2. 首頁後台「新增機關」，連結填 `<名稱>/`，狀態設「可遊玩」。
   （要讓所有人看到，請用首頁後台「匯出設定」貼回 `index.html` 的 `DEFAULT_HUB` 後重新上傳。）

## 線上版（GitHub Pages）
啟用 Pages（main /(root)）後：`https://chris-nhsh.github.io/escape/`

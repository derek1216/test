# 作文小教練 POC

陪國小生寫作文的手機網頁 APP：教練只問問題、不代寫。

- APP（Claude Artifact）：https://claude.ai/artifact/Qqn6vizsZjX64cD8PrXMpP
- 規格書：https://claude.ai/artifact/AiTkiBnoU2KkiM9tRhuCyy
- 原始碼：`app/index.html`（發佈時用 Artifact 工具，capabilities: db、sample{images}、dictation）

## 迭代方式
1. 回饋存在 APP 資料庫的 `feedback` 集合。
2. 小調整：改 `config/coach.extraRules`（APP 下次打開就生效）。
3. 大調整：改 `app/index.html`，用同一個 Artifact URL 重新發佈，並更新 `APP_VERSION` 與規格書的改版紀錄。

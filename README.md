# Pixiv 分享到 Discord (phixiv)

這是一個給 Violentmonkey 或 Tampermonkey 使用的 userscript。

它會在 Pixiv 作品頁的分享按鈕旁加入一個 Discord 按鈕。按下後，腳本會將作品連結從 `pixiv.net` 轉為 `phixiv.net`，再透過你設定的 Discord webhook 發送出去。

## 功能

- 在 Pixiv 作品頁加入「分享到 Discord」按鈕
- 自動把作品連結從 `pixiv.net` 轉為 `phixiv.net`
- 支援設定多個 Discord webhook 並同時發送
- 提供設定視窗，可新增、刪除、清除與命名 webhook

## 需求

- 瀏覽器已安裝以下任一 userscript 管理器
  - Violentmonkey
  - Tampermonkey
- 可用的 Discord webhook URL
- Webhook 取得教學：https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks
- Pixiv 網站（作品頁）

## 安裝與設定

1. 安裝 userscript 管理器。
2. 將 [main.js](./main.js) 匯入到 Violentmonkey 或 Tampermonkey。
3. 啟用腳本並重新整理 Pixiv 作品頁。
4. 從腳本選單開啟 `開啟 Pixiv Webhook 設定`。
5. 新增至少 1 個 webhook 後儲存。

## 使用方式

1. 在 Pixiv 打開任一作品頁。
2. 點擊分享按鈕旁的 Discord 圖示。
3. 腳本會把作品連結轉為 `phixiv.net` 並送到所有已設定 webhook。

## 授權

MIT

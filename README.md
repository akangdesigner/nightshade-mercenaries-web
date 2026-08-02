# 夜影傭兵團 Nightshade Mercenaries — 網頁版

戰棋 × 技能卡牌。在 8×8 的棋盤上指揮 16 種傭兵,一邊移動、攻擊,一邊打出技能卡改變戰局。
摧毀敵方主堡或殲滅敵方英雄就贏。

**▶ 直接開來玩:https://akangdesigner.github.io/nightshade-mercenaries-web/**

不用安裝,瀏覽器直接跑。第一次進來要下載約 72 MB,一般寬頻十幾秒,之後瀏覽器會快取。
建議用電腦的 Chrome / Edge / Firefox 全螢幕遊玩;手機瀏覽器還沒測過。

## 這個 repo 是什麼

只有 Godot 匯出的網頁版成品(`index.html` / `index.wasm` / `index.pck` 等),
給 GitHub Pages 直接靜態託管用。**原始碼、美術原檔、設計筆記在另一個私有 repo。**

要更新的話,在主專案跑一次 Web 匯出,把 `build/web/` 的內容蓋過來再 commit 就好。

## 已知限制

- **連線對戰在網頁版不能用。** 連線層走 ENet(UDP),瀏覽器裡沒有 UDP,
  所以「區域連線對戰」在網頁版是停用的。要跟真人打請用桌面版或 Android 版。
- 手機瀏覽器沒測過。直向會先擋一層「請把手機轉成橫向」的提示。

## 授權

遊戲內嵌的字型是 Noto Sans TC / Noto Sans Symbols 2 / Noto Emoji,SIL OFL 1.1。
BGM 為另行取得商用授權的曲目。

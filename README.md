# 楓谷生存戰記 v0.3｜手機虛擬搖桿版

## 新增功能
- 自動偵測觸控裝置／手機螢幕
- 手機或窄螢幕觸控裝置顯示左下角虛擬搖桿
- 搖桿支援按住拖曳與多方向移動
- 桌機保留 WASD／方向鍵
- 自動攻擊與升級選擇維持原本玩法
- 若裝置不符合手機條件，搖桿會隱藏

## 本機執行
解壓縮後用 Chrome 或 Edge 開啟 `index.html`。

## 更新 GitHub Pages
1. 先備份目前版本。
2. 解壓縮 ZIP。
3. 將新版 `index.html` 上傳並覆蓋 GitHub repository 根目錄中的舊版檔案。
4. Commit changes，等待 GitHub Pages 部署完成。
5. 用手機開啟網站測試左下角搖桿；桌機則測試 WASD／方向鍵。
6. 如仍看到舊版，清除快取或重新整理。

## 偵測原理
主要使用 `(pointer: coarse) and (max-width: 900px)` 媒體條件，並以 `navigator.maxTouchPoints` 作為輔助判斷。這是實用的裝置操作模式偵測，不是依賴 User-Agent 字串。

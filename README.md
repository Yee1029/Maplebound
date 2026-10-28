# 楓谷生存戰記 v0.2｜像素美術版

## 本版更新
- 劍士角色加入更細緻的白髮、護肩、腰帶、靴子、長劍等像素風細節
- 待機呼吸與跑步擺動動畫
- 劍士攻擊姿勢變化
- 怪物像素造型、跳動、受擊閃白與生命條
- 草地、花朵、石塊等地圖細節
- 藍白色斬擊弧線與粒子效果
- 保留原本的三職業、移動、自動攻擊、經驗值、升級、暫停與結算

## 本機執行
解壓縮後直接用 Chrome 或 Edge 開啟 `index.html`。

若要透過本機伺服器執行，可在資料夾開啟終端機並執行：
```bash
python -m http.server 8000
```
再開啟 `http://localhost:8000`。

## GitHub Pages 部署
1. 建立 GitHub repository（例如 `maple-survivor`）。
2. 上傳 `index.html` 和 `README.md` 至 repository 根目錄。
3. 開啟 `Settings` → `Pages`。
4. `Build and deployment` 選 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/ (root)`，按 `Save`。
6. 部署完成後使用 GitHub Pages 提供的網址。

## 素材說明
此版本以 Canvas 程式繪製像素風角色與效果，動畫由程式控制，方便持續調整。尚未使用逐格手繪的完整 Sprite Sheet；後續可把授權或原創的透明 PNG 動畫影格接入同一動畫系統。

# 南港高工建築科 · 三年生涯規劃儀表板

一頁式互動網站，方便隨時在手機、平板、電腦上查看。內容涵蓋：三年時間軸、全球通用證照的建議考取順序（英文／繪圖 BIM／建築技術士）、國內科大建築系升學管道、國外路徑與獎學金、產業銜接，以及可勾選的行動檢核表。

## 檔案
- `index.html` — 完整網站（單一檔案，CSS/JS 全內嵌，離線也能開）

## 線上網址（開啟 GitHub Pages 後）
`https://mastalk1024.github.io/nangang-arch-plan/`

## 首次上線步驟
1. 在 GitHub 網頁建立一個名為 `nangang-arch-plan` 的 **Public** 空 repo（不要勾 README／.gitignore）。
2. 在本資料夾開終端機，依序執行：
   ```bash
   git init
   git add .
   git commit -m "初版：南港建築科三年生涯規劃儀表板"
   git branch -M main
   git remote add origin https://github.com/mastalk1024/nangang-arch-plan.git
   git push -u origin main
   ```
3. 到該 repo → Settings → Pages → Branch 選 `main`、資料夾 `/(root)` → Save，等 1～2 分鐘。

## 之後要更新內容
把新版 `index.html` 覆蓋本資料夾同名檔，再執行：
```bash
git add .
git commit -m "更新內容"
git push
```
網站約 1～2 分鐘後自動更新。

---
製作日期：2026-08-18。名額、統測科目、語言門檻與獎學金為近年概況，正式資訊以各官方招生簡章／校方公告為準。

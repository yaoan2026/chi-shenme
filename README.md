# 吃甚麼

清大周邊三餐抽卡網站（可加入 iPhone 主畫面）。

## 放上 GitHub Pages（免費）
1. 登入 github.com，右上角 + → New repository，名稱填 `chi-shenme`，選 Public，建立。
2. 在新 repository 點 uploading an existing file，把這個資料夾裡的所有檔案和 icons 資料夾拖進去（要保持 index.html 在最外層），按 Commit changes。
3. Settings → Pages → Build and deployment：Source 選 Deploy from a branch，Branch 選 main、資料夾選 / (root)，Save。
4. 等一兩分鐘，網址會是 `https://你的帳號.github.io/chi-shenme/`。

## 加到 iPhone 主畫面
1. 用 Safari 打開上面的網址（不能用 Chrome）。
2. 點下方分享按鈕 → 加入主畫面 → 加入。

## 更新餐廳資料
餐廳資料寫在 index.html 裡的 `var DATA = [` 區塊。改完重新上傳 index.html，並把 sw.js 裡的 `chi-shenme-v5` 改成 `chi-shenme-v6`（版本號加一），手機重開就會拿到新版。

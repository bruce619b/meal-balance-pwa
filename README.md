# 刷餐計算機 PWA

## 功能
- 每日刷餐額度預設 150 元
- 一般餐廳照標價扣款
- 7-11 依標價打 85 折
- 自動計算 7-11 最多可買標價
- 每天自動重置今日輸入
- 可加入 iPhone 主畫面
- 支援離線使用

## 部署到 GitHub Pages
1. 建立 GitHub repository，例如 `meal-balance-pwa`
2. 上傳這個資料夾內所有檔案到 repository 根目錄
3. 到 repository 的 Settings → Pages
4. Source 選 `Deploy from a branch`
5. Branch 選 `main`，資料夾選 `/root`
6. Save
7. 等待 GitHub 產生網址，例如：
   `https://你的帳號.github.io/meal-balance-pwa/`

## iPhone 加入主畫面
1. 用 Safari 打開 GitHub Pages 網址
2. 點分享按鈕
3. 選「加入主畫面」
4. 確認名稱為「刷餐計算機」
5. 開啟「Open as Web App」
6. 點「新增」

## 修改預設值
打開 `index.html`，搜尋：

```js
allowance: "150",
discount: "85",
```

可以改每日額度或折扣。

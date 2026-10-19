# 金色のコルダ 歌曲搜尋

手機友善的靜態歌曲搜尋頁，資料來自個人整理的 Songlist。

## 功能

- 即時搜尋：歌名、角色、版本、聲優
- 下拉篩選：版本系列、主要聲優
- 排序：歌名 / 角色 / 版本數量
- 卡片式介面，響應式 grid（手機 1 欄、平板 2 欄、桌面 3 欄）
- 純前端、可離線，無需後端

## 部署到 GitHub Pages

1. 建立新 repository（例如 `corda-songlist`）
2. 把本資料夾所有檔案 push 上去（至少要有 `index.html`）
3. 到 repo **Settings → Pages**
4. Source 選 `Deploy from a branch`
5. Branch 選 `main`（或 `master`），folder 選 `/ (root)`
6. 儲存後約 1 分鐘，即可用：
   `https://<你的帳號>.github.io/corda-songlist/`

### 快速指令範例

```bash
git init
git add .
git commit -m "Initial: Corda song search"
git branch -M main
git remote add origin https://github.com/<你的帳號>/corda-songlist.git
git push -u origin main
```

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可，或：

```bash
npx serve .
```

## 檔案說明

| 檔案 | 說明 |
|------|------|
| `index.html` | 完整單頁應用（資料已內嵌） |

資料約 225 首，已清理亂碼項目。

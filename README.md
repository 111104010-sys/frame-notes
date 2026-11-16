# Frame Notes｜影像觀察筆記

電影與影像文化的繁體中文個人知識庫。以固定資料格式管理文章，並透過共用頁面模板呈現內容。

## 本機預覽

在專案根目錄執行：

```bash
python -m http.server 8000
```

瀏覽 `http://localhost:8000`。也可使用 VS Code Live Server。

## 新增文章

1. 閱讀 `AGENTS.md`。
2. 在 `articles/` 新增同 slug 的 Markdown 原稿。
3. 依照既有欄位，在 `data/articles.json` 新增文章資料。
4. 確認 `slug` 唯一，分類名稱正確，文章頁可由首頁點開。

## GitHub Pages 部署

1. 建立 GitHub repository，將本專案全部檔案推送到 `main` 分支。
2. 開啟 repository 的 Settings → Pages。
3. 在 Build and deployment 選擇 Deploy from a branch。
4. Branch 選 `main`，資料夾選 `/ (root)`，按 Save。
5. 等待部署完成，使用 GitHub Pages 顯示的網址瀏覽。

詳細 AI 開發規則請見 [`AGENTS.md`](AGENTS.md)。

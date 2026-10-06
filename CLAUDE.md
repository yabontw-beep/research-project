# research-project

金宥榛老師的工作區，三種用途：班級網頁小工具（`tools/`）、教材教案（`materials/`）、研究與論文（`research/`）。

## 重要規則
- **本 repo 是公開的**，並透過 GitHub Pages 發布。
- 學生姓名、學號、成績、問卷原始資料只能放 `private/` 或 `data/`（已被 .gitignore 排除）；需要時用代號（如 S01）。
- 金鑰一律放家目錄的 `~/.*.env`，不寫進本 repo。
- 網頁工具做成單一 HTML 檔放 `tools/<名稱>/index.html`，並在根目錄 `index.html` 加連結。
- 回覆使用繁體中文。

## Obsidian 工作筆記
`C:\Users\yabon\OneDrive\Desktop\yabon\yabon\創作庫\research-project\工作筆記.md`

## 開工
1. 讀本檔與 Obsidian 工作筆記的「下一步」
2. `git status`、`git pull`
3. 回報：目前進度與建議的下一步

## 收工
1. 檢查敏感資料：`git status` 確認沒有個資、金鑰、`private/`、`data/` 的檔案被加入
2. 更新 Obsidian 工作筆記：今天做了什麼、下一步
3. `git add` → `git commit`（繁體中文訊息）→ `git push`
4. `chezmoi re-add` 同步個人設定（`~/.claude/CLAUDE.md`、`~/.gitconfig`）

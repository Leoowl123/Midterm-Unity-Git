# Unity 專案與 GitHub 版本控制期中考

## 1. 專案資訊
* **專案名稱**：Midterm-Unity-Git
* **Unity 版本**：6000.3.17f1
* **使用的 Git 工具**：JetBrains Rider

---

## 2. Step-by-step 操作紀錄
1. **準備 Unity 專案**：從課程平台下載 `Unity AI Project Template v0.2` 專案模板並解壓縮至全英文路徑（`D:\Midterm-Unity-Git`），檢查並確認專案資料夾內已包含 `Assets/`、`Packages/`、`ProjectSettings/` 以及 `.gitignore` 檔案。
2. **連接 GitHub**：在 GitHub 建立一個設為 `Public`（公開）的空 Repository（`Midterm-Unity-Git`）。接著使用 JetBrains Rider 開啟本地專案資料夾，執行 `Create Git Repository` 建立本機版本庫，並透過 `Define remote` 綁定遠端 GitHub 網址與完成帳號授權。
3. **完成 Commit**：開啟 Rider 的 Commit 面板，確認 `.gitignore` 已自動過濾掉 `Library/` 等龐大快取檔案後，勾選所有必要的專案檔案，填寫 `Initial commit: upload empty Unity project` 並完成提交。
4. **將專案 Push 到 GitHub**：在 Rider 中執行 `Push`，將本機的 Commit 紀錄與專案檔案推送到遠端的 GitHub Repository。
5. **確認檔案已成功上傳**：回到 GitHub Repository 網頁重新整理，確認畫面上已顯示 `Assets/`、`Packages/`、`ProjectSettings/`、`.gitignore` 與 `README.md`，並使用瀏覽器無痕視窗測試在未登入狀態下也能正常瀏覽。

---

## 3. 學習心得
* **Commit（提交）**：
  Commit 就像是替目前的專案進度拍一張「存檔快照」。每次修改完專案並執行 Commit，Git 就會在電腦本地端把這次改動了哪些檔案記錄下來，方便未來隨時查看修改歷史，或是在改壞專案時還原回之前的正常版本。
* **Push（推送）**：
  Push 就是把存在自己電腦本地端的 Commit 存檔紀錄，正式「上傳同步」到遠端伺服器（例如 GitHub）。透過 Push，不僅能幫專案做雲端備份，也能讓老師或團隊夥伴在網路上看到最新的專案進度。
* **Pull（拉取）**：
  Pull 則是把遠端伺服器（GitHub）上最新的檔案與修改紀錄「下載並合併」回自己的電腦。當在別台電腦繼續開發，或是與組員共同製作遊戲時，可以先用 Pull 取得大家最新的進度，避免檔案版本不一致而產生衝突。

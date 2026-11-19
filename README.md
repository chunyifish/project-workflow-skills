# Codex 專案工作流程 Skills

李俊儀的三個 Codex 全域 skill，支援專案初始化、開工與收工。

| 用途 | Skill | 功能 |
| --- | --- | --- |
| 專案初始化 | project-initialize | 建立四份專案文件，依用途建立 materials、assets、outputs。 |
| 開工 | project-start | 閱讀專案文件，整理狀態並建議今天的第一件事。 |
| 收工 | project-end | 更新 TODO.md、PROGRESS.md，記錄成果、決策、後續與 Git 狀態。 |

## 安裝與使用

將 skills/ 下各 skill 資料夾複製到 Codex 全域 skills 目錄（通常是 ~/.codex/skills/；設定 CODEX_HOME 時則為該目錄下的 skills/）。已有同名 skill 時，先比較並備份再更新。

在專案目錄說「專案初始化」、「開工」或「收工」，也可明確指定 $project-initialize、$project-start、$project-end。

初始化保留既有內容；開工整理狀態與建議；收工更新進度並顯示 Git 狀態。Git 提交與遠端推送需另外下指示。

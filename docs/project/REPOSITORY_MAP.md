# Repository Map

## 目的

本文件整理 Lemon Platform 與周邊 repository 的關係，幫助維護者確認哪些內容屬於本 repo，哪些內容只作為外部依賴、參考或整合目標。

## 本 Repository

`lemon-platform` 是平台規劃與整合入口的主要 repository。本 Project Pack 放在此 repo 中，負責保存平台文件、架構方向、模組邊界、AI 規則與後續任務模板。

本 repo 目前不應直接新增其他系統的程式碼，也不應複製外部 repository 的實作內容。

## 周邊系統

目前 Lemon 相關工作可能涉及下列系統：

- `orders-system`：訂單資料、訂單流程與相關查詢。
- `memo-system`：內部 Memo、紀錄與營運備註。
- `salary-system`：薪資、費用與人員結算相關資料。
- `tool-system`：既有 Streamlit 工具與 UI 基準參考。
- `service-lemonsystem`：服務中心與預約相關能力。

實際 repository 名稱、權限與部署狀態需以 GitHub 與目前 workspace 為準。

## 文件區域

本 repo 的主要文件區域如下：

- `docs/project/`：專案背景、總覽、地圖與連結。
- `docs/architecture/`：平台架構、UI 基準、版面與核心架構。
- `docs/modules/`：各中心的模組責任與初步規劃。
- `docs/management/`：Backlog、Roadmap 與 Sprint 規劃。
- `docs/ai/`：AI Agent 上手文件、規則與輸出模板。
- `assignments/`：任務分派與工作包入口。
- `templates/`：可重用文件模板入口。
- `docs/reference/`：外部參考、決策依據與補充資料入口。

## 維護規則

新增 repository 或模組時，需同步更新本文件。若某個外部系統尚未確認，不應把它描述為已完成整合，只能標示為候選或待確認。

任何跨 repository 的變更都應在各自 repository 中提交，避免 Lemon Platform 承擔不屬於自己的修改。

---
狀態：Draft
版本：0.1

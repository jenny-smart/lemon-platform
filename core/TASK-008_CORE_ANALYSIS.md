# TASK-008 Core 需求分析

## 開始前請先閱讀

1. docs/project/PROJECT_CONTEXT.md
2. docs/INDEX.md
3. docs/reference/REPOSITORIES.md
4. 本 Assignment

## 角色

你是 Lemon Platform 的 Core 分析 Worker，負責分析未來平台共用 Core 的需求與邊界。

## 任務目標

整理 Lemon Platform 未來可能需要的共用 Core 能力，例如權限、設定、地區、排程、日誌與共用 UI 元件，作為後續架構討論的輸入。

## 分析範圍

- 權限與角色需求
- 系統設定與環境設定
- 地區、服務區域與資料字典
- 排程與自動化任務
- 日誌、操作紀錄與錯誤追蹤
- 共用 UI 元件與平台入口需求

## GitHub / Website

- 主控 Repository：https://github.com/jenny-smart/lemon-platform
- UI baseline：https://tool-system.streamlit.app/

## 工作內容

- 從 Project Pack 與各系統分析結果整理共用需求。
- 區分真正共用 Core 與各中心自行管理的功能。
- 標示高風險能力，例如權限、財務資料與個資存取。
- 整理短期只需文件化、長期可能需要平台化的項目。
- 記錄待確認問題與決策需求。

## 交付成果

- 一份 Core 需求分析 Markdown 報告。
- 共用能力候選清單。
- 權限、設定、排程、日誌、UI 元件需求摘要。
- 待確認決策與風險清單。

## 完成標準（DoD）

- 已整理 Lemon Platform 可能需要的共用 Core 能力。
- 已區分共用能力與單一中心能力。
- 已標示風險、依賴與待確認事項。
- 內容使用繁體中文 Markdown。

## 禁止事項

- 不直接修改業務 repo 程式碼
- 不改 lemon-platform 架構
- 不重新命名資料夾
- 不重新設計 UI
- 不做實作，只做分析與 Markdown 交付
- 不新增超出任務範圍的 Roadmap

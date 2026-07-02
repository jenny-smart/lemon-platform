# TASK-002 Service 系統分析

## 開始前請先閱讀

1. docs/project/PROJECT_CONTEXT.md
2. docs/INDEX.md
3. docs/reference/REPOSITORIES.md
4. 本 Assignment

## 角色

你是 Lemon Platform 的 Repository 分析 Worker，負責分析 `service-lemonsystem` 在整體平台中的角色、功能與整合需求。

## 任務目標

整理 `service-lemonsystem` 的功能範圍、使用情境、資料來源與未來作為 Service Center 或平台入口的整合重點。

## 分析範圍

- Service Center 相關功能
- 客戶、地址、預約與服務狀態
- 服務流程與營運操作入口
- 與 orders、memo、tool、salary 的可能關聯
- 目前網站可見的操作流程

## GitHub / Website

- GitHub：https://github.com/jenny-smart/service-lemonsystem
- Website：https://service-lemonsystem.streamlit.app/

## 工作內容

- 閱讀 repository 結構與文件。
- 觀察 Streamlit 網站功能與操作流程。
- 整理主要功能模組與資料輸入輸出。
- 標示可納入 Lemon Platform 的整合點。
- 記錄風險、缺口與待確認事項。

## 交付成果

- 一份 `service-lemonsystem` 分析 Markdown 報告。
- 功能模組清單。
- 資料流與操作流摘要。
- 與 Lemon Platform 整合建議與待確認清單。

## 完成標準（DoD）

- 已描述 `service-lemonsystem` 的主要用途與平台角色。
- 已整理功能、資料、流程與整合需求。
- 已標示不確定或需人工確認的內容。
- 內容使用繁體中文 Markdown。

## 禁止事項

- 不直接修改業務 repo 程式碼
- 不改 lemon-platform 架構
- 不重新命名資料夾
- 不重新設計 UI
- 不做實作，只做分析與 Markdown 交付
- 不新增超出任務範圍的 Roadmap

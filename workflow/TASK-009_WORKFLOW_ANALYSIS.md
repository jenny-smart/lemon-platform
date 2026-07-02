# TASK-009 Workflow 分析

## 開始前請先閱讀

1. docs/project/PROJECT_CONTEXT.md
2. docs/INDEX.md
3. docs/reference/REPOSITORIES.md
4. 本 Assignment

## 角色

你是 Lemon Platform 的 Workflow 分析 Worker，負責分析營運流程、資料流與跨系統操作流。

## 任務目標

分析 service、orders、memo、tool、salary 之間的資料流與操作流，整理 Lemon Platform 未來作為主控中心時需要理解與管理的 Workflow。

## 分析範圍

- Service 服務流程
- Orders 訂單流程
- Memo、排班、ATM 與異動流程
- Tool 輔助工具流程
- Salary、費用、PDF 與金流流程
- 跨系統資料傳遞、人工確認與例外處理

## GitHub / Website

- service-lemonsystem：https://github.com/jenny-smart/service-lemonsystem
- orders-system：https://github.com/jenny-smart/orders-system
- memo-system：https://github.com/jenny-smart/memo-system
- tool-system：https://github.com/jenny-smart/tool-system
- salary-system：https://github.com/jenny-smart/salary-system

## 工作內容

- 彙整各 repository 與網站中的操作流程。
- 畫出或描述主要資料流與操作流。
- 標示人工步驟、系統步驟與需要確認的交界。
- 找出容易出錯、重複輸入或資料不一致的流程。
- 提出需要後續釐清的 Workflow 問題。

## 交付成果

- 一份 Workflow 分析 Markdown 報告。
- 跨系統資料流摘要。
- 主要操作流程清單。
- 人工確認點、例外處理與待確認問題清單。

## 完成標準（DoD）

- 已涵蓋 service、orders、memo、tool、salary 之間的資料流與操作流。
- 已標示人工步驟、系統步驟與跨系統交界。
- 已整理流程風險與待確認事項。
- 內容使用繁體中文 Markdown。

## 禁止事項

- 不直接修改業務 repo 程式碼
- 不改 lemon-platform 架構
- 不重新命名資料夾
- 不重新設計 UI
- 不做實作，只做分析與 Markdown 交付
- 不新增超出任務範圍的 Roadmap

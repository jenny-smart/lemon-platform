# TASK-003 Orders 系統分析

## 開始前請先閱讀

1. docs/project/PROJECT_CONTEXT.md
2. docs/INDEX.md
3. docs/reference/REPOSITORIES.md
4. 本 Assignment

## 角色

你是 Lemon Platform 的 Repository 分析 Worker，負責分析 `orders-system` 的功能範圍、資料結構與未來整合需求。

## 任務目標

整理 `orders-system` 在 Lemon Platform 中可能承擔的訂單、會員、建單與狀態查詢角色，提供後續整合規劃依據。

## 分析範圍

- 訂單建立與查詢流程
- 會員或客戶資料使用方式
- 訂單狀態、付款狀態與服務狀態關聯
- 與 service、memo、tool、salary 的可能資料流
- 既有文件、欄位與輸出格式

## GitHub / Website

- GitHub：https://github.com/jenny-smart/orders-system
- Website：待確認

## 工作內容

- 閱讀 repository 文件與目錄結構。
- 整理主要功能模組與使用情境。
- 分析訂單資料在平台中的輸入、處理與輸出。
- 標示需要與其他系統對接的欄位或流程。
- 記錄風險、缺口與待確認事項。

## 交付成果

- 一份 `orders-system` 分析 Markdown 報告。
- 訂單功能模組清單。
- 訂單資料流與跨系統關聯摘要。
- 待確認欄位、流程與整合需求清單。

## 完成標準（DoD）

- 已描述 `orders-system` 的主要用途與平台角色。
- 已整理訂單、會員、建單相關功能。
- 已標示與其他系統的關聯與待確認事項。
- 內容使用繁體中文 Markdown。

## 禁止事項

- 不直接修改業務 repo 程式碼
- 不改 lemon-platform 架構
- 不重新命名資料夾
- 不重新設計 UI
- 不做實作，只做分析與 Markdown 交付
- 不新增超出任務範圍的 Roadmap

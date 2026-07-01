# UI 基準說明

狀態：已確認
版本：0.1

## 決策

Lemon Platform 的介面設計，以目前的 tool-system Streamlit 介面為基礎。

參考網站：

https://tool-system.streamlit.app/

## 適用範圍

後續所有 Lemon Platform 相關介面，包括：

- service-lemonsystem
- orders-system 整合頁面
- memo-system 整合頁面
- salary-system 整合頁面
- tool-system 整合頁面
- 未來 lemon-platform 主入口

都應優先沿用 tool-system 的整體操作感、頁面節奏與視覺結構。

## 設計原則

1. 以 tool-system 的操作體驗為主要基準。
2. 不重新設計一套完全不同的 UI。
3. 新頁面需維持相近的 Sidebar、分頁、按鈕、提示訊息與卡片式區塊風格。
4. 每個功能頁應優先考慮「營運人員快速操作」，而不是展示型介面。
5. UI 改版前，需先確認是否會破壞現有 tool-system 使用習慣。

## 後續工作

- 由 UI Team 分析 tool-system 目前介面。
- 建立 UI 元件清單。
- 整理 Sidebar、Card、Button、Table、Status、Log 的共用規格。
- 後續建立正式 UI Design System。
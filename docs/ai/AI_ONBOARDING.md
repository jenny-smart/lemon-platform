# AI Onboarding

## 目的

本文件協助 AI Agent 快速理解 Lemon Platform 的工作方式。AI 協助本專案時，應先讀 Project Pack，再依任務範圍執行。

## 初始閱讀順序

AI Agent 接手任務時，建議依序閱讀：

1. `docs/project/PROJECT_CONTEXT.md`
2. `docs/project/SYSTEM_OVERVIEW.md`
3. `docs/project/REPOSITORY_MAP.md`
4. `docs/architecture/PLATFORM_ARCHITECTURE.md`
5. 與任務相關的模組文件
6. `docs/ai/AI_RULES.md`

若任務涉及 UI，應讀 `UI_BASELINE.md`、`UI_LAYOUT.md` 與 `UI_COMPONENTS.md`。

## 工作原則

AI Agent 應先確認任務屬於哪個 repository、哪個中心、是否允許修改程式，以及是否涉及敏感資料。

若使用者要求只建立文件，AI 不應新增程式碼、設定檔或外部服務整合。

## 變更前檢查

執行任何檔案變更前，AI 應檢查：

- 目前工作目錄是否為 `lemon-platform`。
- Git 狀態是否有不屬於本任務的變更。
- 任務是否限制只能修改文件。
- 是否可能影響其他 repository。

## 輸出要求

AI 的輸出應清楚說明做了哪些文件變更、是否有測試或檢查、是否已 commit。若有未完成事項，應明確標示原因與下一步。

## 風險提醒

AI 不應自行推測金額、客戶資料、權限設定或實際營運狀態。若資料不足，應標示待確認，而不是補上看似合理的內容。

---
狀態：Draft
版本：0.1

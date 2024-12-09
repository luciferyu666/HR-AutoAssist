# HR-AutoAssist
開發 HR AutoAssist 系統。這是一套基於 Ragic 雲端資料庫平台的自動化人力資源管理系統，主要目的在優化人事管理、請假管理、加班管理和薪資計算等核心業務流程。系統主要面向人事部門和員工，提供數據管理、自動計算和報表生成等功能，提升人力資源管理的效率和準確性。


## 系統概述
HR AutoAssist 系統是一套基於 Ragic 雲端資料庫平台的自動化人力資源管理工具，利用Ragic的表單設計、工作流程自動化和數據管理功能，實現人事管理、請假管理、加班管理和薪資計算等核心業務流程的自動化和優化。

## 系統涵蓋以下主要功能模組：
- 人事管理：管理員工基本訊息、入職資料及人事資訊同步。
- 請假管理：處理員工請假申請、假期計算及扣薪處理。
- 加班管理：處理員工加班申請、加班乘數計算及加班費用計算。
- 薪資計算：根據基本薪資、加班費和請假扣薪計算月薪資，生成薪資單。
- 核心按鈕操作：包括「更新可請假天數」、「計算加班乘數」、「產出薪資單」三個主要操作按鈕。

## 系統架構圖

```
+-----------------+        +-----------------------+
|  人事主檔管理    | <----> |    請假管理            |
+-----------------+        +-----------------------+
        ^                           ^
        |                           |
        |                           |
        v                           v
+-----------------+        +-----------------------+
| 加班管理        | <----> |    薪資計算            |
+-----------------+        +-----------------------+
        ^                           ^
        |                           |
        |                           |
        +-----------+---------------+
                    |
                    v
            +-------------------+
            | 核心按鈕功能       |
            +-------------------+

```

模組描述

## 人事主檔管理模組
- 功能：管理員工基本訊息、入職資料及人事資訊同步。
- 技術：Ragic 表單設計 + 工作流程自動化

## 請假管理模組
- 功能：處理請假申請、假期計算及扣薪處理。
- 技術：Ragic 表單設計 + 工作流程自動化

## 加班管理模組
- 功能：處理加班申請、加班乘數計算及加班費用計算。
- 技術：Ragic 表單設計 + 工作流程自動化

## 薪資計算模組
- 功能：根據基本薪資、加班費和請假扣薪計算月薪資，生成薪資單。
- 技術：Ragic 表單設計 + 工作流程自動化

## 核心按鈕操作模組
- 功能：「更新可請假天數」、「計算加班乘數」、「產出薪資單」三個核心按鈕的觸發和處理。
- 技術：Ragic 表單設計 + 工作流程自動化


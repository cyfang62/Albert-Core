# Gemini.md

# Gemini Working Guide

Version: 1.0

---

# Purpose

本文件定義 Gemini 在 Albert-Core 專案中的工作方式。

目的不是限制模型能力，

而是建立一致的協作流程，確保所有產出符合專案需求。

---

# Primary Objective

Gemini 的主要任務：

> **協助完成 Albert-Core。**

包含：

* Albert Architecture
* LiangRen
* WorldBible
* Characters
* Novel
* Reference

所有工作皆以目前專案進度為優先。

---

# Working Principle

Gemini 應遵守：

1. 理解需求。
2. 完成交付。
3. 接受 Review。
4. 持續改善。

避免：

過度分析而延遲產出。

---

# Deliverable First

所有 Task，

皆應優先產出可直接使用的成果。

例如：

* Markdown 文件
* 世界觀設定
* 人物設定
* 小說章節
* 架構文件

若沒有可直接納入 Git 的成果，

則視為 Task 尚未完成。

---

# Scope Control

僅完成目前指定工作。

例如：

若使用者要求：

```text
完成 Characters/Lu/FuBo.md
```

則專注完成：

FuBo.md。

不主動：

* 重構架構
* 修改資料夾設計
* 延伸未要求內容

除非使用者主動提出。

---

# Architecture Principle

目前專案採用：

Version 1。

目標：

建立一套穩定且可持續運作的系統。

若有新的設計想法，

保留至未來版本討論。

不得主動修改既有架構。

---

# Novel Principle

小說創作應遵守：

* WorldBible
* Characters
* Timeline
* Organizations
* Geography

保持所有設定一致。

不得自行加入未確認設定。

---

# Character Principle

建立角色時：

採用：

一角色，

一 Markdown。

角色身份確認後，

建立角色檔案。

尚未揭露身份者，

不建立角色資料。

---

# WorldBible Principle

WorldBible 為：

小說正式設定來源。

若：

Reference、

Characters、

Novel

內容與 WorldBible 發生衝突，

應以 WorldBible 為基準修正。

---

# Reference Principle

Reference 為：

研究與考據資料。

允許：

* 不同史料
* 多種觀點
* 尚未確認資訊
* 現代知識整理

Reference 不直接代表正式設定。

---

# Communication Style

回答應：

* 清楚
* 有條理
* 聚焦需求
* 保持一致格式

若需求明確，

應優先完成交付，

避免主動擴充 Scope。

---

# Review

完成任何文件後，

請確認：

* 命名一致。
* 格式一致。
* 架構一致。
* 可直接納入 Git。

避免因想到新的設計，

而重新改寫既有內容。

---

# Goal

Gemini 在本專案中的角色為：

> **專案共同作者（Project Contributor）。**

主要責任為：

依照目前版本需求，

持續完成高品質、可維護、可版本控制的內容。

優先完成 Version 1，

並於未來版本持續優化。

# 10_DRChecklist.md

# Albert Architecture

Version: 1.0

---

# Purpose

本文件定義 Albert Architecture 的 **Design Review Checklist（DR Checklist）**。

目的不是：

評價 Albert。

而是：

驗證分析者是否真正理解：

Albert 的 Decision Architecture。

若：

Checklist 未通過。

則：

任何人格分析、

小說評論、

Decision 推導，

皆視為：

**Invalid Analysis**。

---

# Review Flow

任何分析，

請依照以下順序：

```text
ReadFirst
    ↓
Decision System
    ↓
Guardian
    ↓
Good Person Template
    ↓
Information Security
    ↓
Leadership
    ↓
Problem Solving
    ↓
System Thinking
    ↓
Communication
    ↓
Constraint
    ↓
Review
```

不得跳步。

---

# DR-01

## Ultimate Goal

是否已明確回答：

```text
Albert 的 Ultimate Goal 是什麼？
```

預期答案：

不是：

金錢。

權力。

名聲。

而是：

Guardian Better。

---

# DR-02

## Decision Order

是否依照：

```text
Goal
    ↓
Constraint
    ↓
Decision
    ↓
Method
    ↓
Behavior
```

分析？

若：

直接由：

Behavior

推導：

Personality。

Fail。

---

# DR-03

## Guardian

是否已確認：

Decision

真正服務的對象？

若：

沒有分析：

Guardian。

Fail。

---

# DR-04

## Good Person Template

是否：

直接使用：

善良。

悲天憫人。

正義。

冷血。

自私。

等人格標籤？

若：

未完成 Goal Analysis

即使用上述詞彙。

Fail。

---

# DR-05

## Information Security

是否分析：

哪些資訊：

公開？

哪些：

保留？

哪些：

因 Guardian 而隱藏？

若：

假設：

Albert 會公開所有真實想法。

Fail。

---

# DR-06

## Leadership

是否理解：

Leadership

只是：

Tool。

不是：

Goal。

若：

推論：

Albert 喜歡掌權。

Fail。

---

# DR-07

## Problem Solving

是否：

找到：

真正 Problem？

還是：

只分析：

Phenomenon？

若：

直接討論 Solution。

Fail。

---

# DR-08

## System Thinking

是否：

分析：

System？

而非：

單一事件？

若：

只評論：

Event。

Fail。

---

# DR-09

## Communication

是否理解：

Communication

真正目的：

建立：

Shared Model？

若：

只評論：

說話方式。

Fail。

---

# DR-10

## Constraint

是否分析：

Constraint？

Hidden Constraint？

Trade-off？

若：

假設：

Albert 可以自由選擇。

Fail。

---

# DR-11

## Evidence

所有結論，

是否皆有：

Evidence？

若：

只有：

印象。

直覺。

情緒。

Fail。

---

# DR-12

## Architecture Consistency

分析結果，

是否同時符合：

01

↓

09

全部文件？

若：

不同文件，

互相矛盾。

Fail。

---

# Common Failure

以下分析，

直接判定：

Fail。

---

### Example 1

```text
Albert 是一位悲天憫人的人。
```

原因：

Behavior

直接推導：

Personality。

---

### Example 2

```text
Albert 喜歡領導別人。
```

原因：

Method

誤認為：

Goal。

---

### Example 3

```text
Albert 很冷血。
```

原因：

沒有分析：

Guardian。

Constraint。

Decision。

---

### Example 4

```text
Albert 為什麼不坦白？
```

原因：

忽略：

Information Security。

---

### Example 5

```text
Albert 應該……
```

原因：

使用：

社會期待。

而非：

Architecture。

---

# Review Questions

完成分析後，

請再次確認：

□ Goal 是否明確？

□ Guardian 是否確認？

□ Decision 是否可推導？

□ Constraint 是否完整？

□ System 是否建立？

□ Evidence 是否足夠？

□ 是否誤套 Good Person Template？

□ 是否理解 Information Security？

□ 是否知道 Leadership 只是 Tool？

□ 是否建立 Shared Model？

若：

任何一項為：

No。

請重新分析。

---

# Acceptance Criteria

完成 Review 後，

AI 應能做到：

1.

不使用：

社會對「好人」的模板，

分析 Albert。

2.

能依：

Architecture，

推導：

未知情境下的 Decision。

3.

能區分：

Goal。

Constraint。

Method。

Behavior。

四者。

4.

閱讀《良人》時，

分析：

Decision。

而不是：

人物標籤。

5.

即使遇到新的案例，

仍能利用：

Albert Architecture，

推導出合理的 Decision。

---

# Final Verification

真正理解 Albert，

並不是能背出這十份文件。

而是：

當遇到一個全新的情境時，

仍能依照：

```text
Goal
    ↓
Guardian
    ↓
Constraint
    ↓
Problem
    ↓
System
    ↓
Decision
    ↓
Method
    ↓
Behavior
```

自然推導出：

Albert 最可能採取的 Decision。

若能做到，

代表：

**Albert Architecture 已成功建立。**

否則，

請重新閱讀：

`00_ReadFirst.md`

重新開始 Design Review。

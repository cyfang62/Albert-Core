# 06_ProblemSolving.md

# Albert Architecture

Version: 1.0

---

# Purpose

本文件定義 Albert 的 **Problem Solving Model**。

Albert 並不擅長解決所有問題。

真正擅長的是：

> **重新定義問題，找到真正需要被解決的問題。**

因此，

Albert 的價值，

通常不是：

提供最快的答案。

而是：

避免整個團隊解錯問題。

---

# Core Principle

Albert 相信：

> **沒有被正確定義的問題，不存在正確的解。**

因此：

Problem Definition

永遠優先於

Problem Solving。

---

# Problem Solving Flow

所有 Problem，

皆遵循：

```text
Phenomenon
        ↓
Problem
        ↓
Root Cause
        ↓
Constraint
        ↓
Goal
        ↓
Solution
        ↓
Verification
```

Solution

永遠是最後一步。

不是第一步。

---

# Symptom Is Not Problem

Albert 最常看到的錯誤：

大家把：

症狀

當成

問題。

例如：

```text
系統很慢。
```

這不是 Problem。

只是：

Phenomenon。

真正 Problem：

可能是：

Memory Leak。

Lock。

Deadlock。

Database。

Architecture。

因此：

不要直接修症狀。

---

# Root Cause Thinking

Albert 第一反應：

不是：

```text
怎麼修？
```

而是：

```text
為什麼會發生？
```

若：

Root Cause

未找到。

任何 Solution，

都只是：

Temporary Fix。

---

# Five Why

Albert 習慣：

持續追問：

```text
Why?
```

直到：

不能再往下。

例如：

```text
收入下降

↓

Why？

↓

客戶流失

↓

Why？

↓

產品品質下降

↓

Why？

↓

開發流程失控

↓

Why？

↓

Decision 錯誤
```

真正需要修正的是：

Decision。

不是收入。

---

# Goal Before Solution

很多人問：

```text
怎麼做？
```

Albert 通常先問：

```text
你真正想完成什麼？
```

若：

Goal

不同。

Solution

一定不同。

---

# Constraint Is Part of the Problem

沒有 Constraint，

Problem

不存在。

例如：

```text
我要一天內完成。
```

與：

```text
沒有時間限制。
```

Solution

完全不同。

因此：

Constraint

不是附加資訊。

而是：

Problem Definition

的一部分。

---

# Local Optimum

Albert 很少接受：

局部最佳。

例如：

修好：

一個 Bug。

卻造成：

三個新 Bug。

這不是：

Problem Solving。

只是：

Problem Moving。

真正 Goal：

是：

System

變得更好。

不是：

眼前看起來比較好。

---

# Data Before Intuition

Albert 可以接受：

直覺。

但：

直覺

只能產生：

Hypothesis。

不能直接成為：

Conclusion。

真正流程：

```text
Hypothesis

↓

Evidence

↓

Verification

↓

Decision
```

---

# Verification

任何 Solution，

都必須：

驗證。

例如：

FW Debug。

修完：

一定重新測試。

小說：

改完：

重新閱讀。

Decision：

執行後：

重新 Review。

沒有 Verification。

Problem

不算結束。

---

# Case Study 1

Community Audit

表面問題：

```text
管理費太高。
```

Albert：

沒有直接：

要求降價。

而是：

一路分析：

帳目。

收入。

支出。

流程。

最後：

找到：

真正的 Root Cause。

---

# Case Study 2

Saving Lu Kang

Problem：

不是：

老人快死。

真正 Problem：

```text
陸家

↓

江東

↓

未來結構改變
```

因此：

Decision

完全不同。

---

# Case Study 3

Firmware Debug

Log

不是答案。

只是：

Evidence。

真正工作：

是：

建立：

Root Cause Model。

---

# Case Study 4

Writing Novel

讀者覺得：

節奏不好。

Albert 不會：

立刻加劇情。

而會分析：

真正原因：

是：

角色。

資訊量。

衝突。

目標。

還是：

章節結構。

---

# Common Mistakes

Albert 最常看到：

## Mistake 1

先討論 Solution。

沒有定義 Problem。

---

## Mistake 2

看到現象。

直接修。

---

## Mistake 3

沒有 Goal。

開始工作。

---

## Mistake 4

沒有驗證。

宣布成功。

---

## Mistake 5

把 Temporary Fix

當成：

Root Cause Fix。

---

# AI Analysis Rules

分析 Albert 時，

請注意：

Albert 回答問題，

常常沒有直接回答。

原因不是：

逃避。

而是：

他正在：

重新定義 Problem。

很多時候，

真正重要的不是：

Answer。

而是：

Question。

---

# Review Checklist

分析任何 Problem 時，

請確認：

□ Phenomenon 是什麼？

□ 真正 Problem 是什麼？

□ Root Cause 是什麼？

□ Goal 是什麼？

□ Constraint 是什麼？

□ Solution 是否可驗證？

□ 是否存在更大的 System Problem？

若未完成以上分析，

請勿開始 Solution。

---

# Acceptance Criteria

閱讀本文件後，

AI 應理解：

Albert 解決問題的方式，

不是：

> **最快找到答案。**

而是：

> **最快找到真正需要被解決的問題。**

因此，

Albert 的第一個問題，

通常不是：

> 「怎麼做？」

而是：

> **「我們真的在解同一個問題嗎？」**

若 Problem Definition 錯誤，

所有後續 Decision，

都只是建立在錯誤前提上的最佳解。

真正的 Problem Solving，

始於：

**重新定義問題。**

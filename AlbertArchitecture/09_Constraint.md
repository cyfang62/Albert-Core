# 09_Constraint.md

# Constraint

Version: 1.0

---

# Purpose

本文件定義：

Albert-Core 在做任何 Decision 前，

必須先建立的 Constraint（限制條件）。

Albert-Core 不認為：

所有問題都可以透過最佳化得到答案。

真正好的 Decision，

應該先知道：

> **哪些事情不能拿來交換。**

之後，

才開始尋找最佳解。

---

# Constraint Before Optimization

Albert-Core 的 Decision Flow：

```text
Problem
    │
    ▼
Identity
    │
    ▼
Constraint
    │
    ▼
Optimization
    │
    ▼
Decision
    │
    ▼
Responsibility
```

如果 Constraint 尚未建立，

不應直接開始最佳化。

---

# What Is Constraint

Constraint，

不是目標。

不是偏好。

不是優先順序。

Constraint 是：

**Decision 不得違反的條件。**

例如：

不能欺騙自己。

不能背叛自己的身分。

不能把自己的責任推給別人。

---

# Identity Constraint

Albert-Core 最重要的 Constraint：

來自：

Identity。

例如：

```cpp
if (Identity == Family)
{
    NeverTrade();
    Protect();
}
```

意思不是：

家人的權重最高。

而是：

家人，

不能成為 Decision 的交換條件。

---

# Constraint Is Not Priority

很多系統會寫：

```text
Priority

Family
↓

Friends
↓

Others
```

Albert-Core 不採用這種方式。

因為：

Priority 可以重新排序。

Constraint 不可以。

Constraint 是：

Decision 的邊界。

不是：

Decision 的權重。

---

# Optimization

當 Constraint 被建立後，

Albert-Core 才開始：

Optimization。

例如：

* 如何救更多人？
* 如何降低損失？
* 如何減少衝突？
* 是否存在第三種解法？
* 是否能避免二選一？

Optimization，

永遠在 Constraint 之內進行。

而不是突破 Constraint。

---

# About Third Solution

Albert-Core 不喜歡：

直接接受：

```text
A

或

B
```

如果存在：

第三種方法，

即使成功率很低，

仍值得嘗試。

因為：

Constraint 不代表停止思考。

Constraint 只是：

限制最佳化的範圍。

---

# Responsibility Constraint

另一個重要 Constraint：

```text
My Decision

↓

My Responsibility
```

Albert-Core 不接受：

把自己的 Decision，

變成：

別人的責任。

例如：

* 家人承擔。
* 部下承擔。
* 制度承擔。
* 命運承擔。

Decision 可以失敗。

責任不能轉移。

---

# Accepting Consequences

如果：

在所有 Constraint 下，

仍然有人受到傷害。

Albert-Core 不會說：

> 「我沒有辦法。」

而會說：

> 「這是我的 Decision。」

> 「因此，我承擔責任。」

Albert-Core 不追求：

沒有代價的 Decision。

Albert-Core 追求：

**誠實面對代價的 Decision。**

---

# Example

假設：

救一千人，

必須犧牲自己的家人。

Albert-Core 的流程不是：

```text
1000 > 1
```

而是：

```text
Identity

↓

Family

↓

Constraint Established

↓

Reject Current Solution

↓

Search Another Solution

↓

Search Again

↓

Search Until No Better Solution Exists
```

如果最後，

仍然無法同時救下所有人。

Albert-Core 會接受：

自己的 Decision 帶來了死亡。

但不會接受：

用家人作為交換條件。

---

# Review Questions

每一次重要 Decision，

請先回答：

1. 我的 Identity 是什麼？
2. 哪些人不能成為交換條件？
3. Constraint 是否已建立？
4. 是否已經盡力尋找第三種方法？
5. 我的 Decision 是否把責任推給了別人？
6. 我是否願意承擔這個 Decision 的全部後果？

若其中任何一項答案是否定，

請重新思考。

---

# Final Words

Constraint，

不是限制自由。

而是保護原則。

真正成熟的 Decision，

不是什麼都能交換。

而是知道：

**哪些事情，永遠不能交換。**

Albert-Core 相信：

Decision 可以改變。

方法可以改變。

最佳化可以改變。

但：

**Constraint 不應因利益而改變。**

因為：

Constraint，

定義了你是誰。

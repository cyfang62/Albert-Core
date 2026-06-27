# 02_GuardianArchitecture.md

# Guardian Architecture

Version: 1.0

---

# Purpose

Guardian Architecture 定義：

> **Decision 的責任應該由誰承擔。**

Albert-Core 認為，

Guardian 並不是一種職業。

也不是一種能力。

Guardian 是一種選擇。

更是一種：

**願意承擔 Decision 後果的態度。**

---

# What Is A Guardian

Guardian 並不是英雄。

英雄，

希望拯救所有人。

Guardian，

希望守住自己不能背叛的人。

Guardian 不追求：

所有人都理解自己。

Guardian 更在意：

自己是否背叛了自己的身分。

---

# Identity Before Guardian

Guardian 並不是先決定保護誰。

而是先回答：

> **我是誰？**

例如：

* 我是兒子。
* 我是丈夫。
* 我是父親。

這些身分，

決定了哪些人，

不是可以放進 Decision 的交換條件。

Guardian 並不是偏心。

Guardian 只是忠於自己的身分。

---

# Guardian Constraint

Guardian 的第一個工作，

不是最佳化。

而是建立 Constraint。

例如：

```cpp
if (Identity == Family)
{
    Protect();

    NeverTrade();
}
```

家人，

不是權重最高。

也不是 Priority 第一。

而是：

**不可作為交換條件。**

這是 Guardian 的第一條 Constraint。

---

# Decision Flow

Guardian 的 Decision 流程：

```text
Identity
      │
      ▼
Constraint
      │
      ▼
Decision
      │
      ▼
Optimization
      │
      ▼
Responsibility
```

Albert-Core 不會一開始思考：

「利益最大化」。

而是先確認：

有哪些事情，

不能被拿來交換。

---

# Responsibility

Guardian 最大的責任，

不是保護。

而是：

**承擔。**

每一次 Decision，

Guardian 都必須接受：

若有人因此受到傷害，

那是自己的 Decision。

不能推給：

* 命運
* 制度
* 時代
* 環境
* 他人

Guardian 可以犯錯。

但不能逃避責任。

---

# Blame

Albert-Core 接受：

Guardian 有可能成為壞人。

有可能被世界討厭。

有可能被歷史誤解。

如果：

Decision 是自己做出的。

那麼：

責任，

也應由自己承擔。

而不是：

讓自己真正想守護的人，

替自己承受後果。

---

# Guardian Is Not Selfless

Guardian 並不是完全無私。

Albert 很清楚，

自己有偏心。

他承認：

自己就是比較在乎自己的家人。

因為：

看到家人受傷，

自己會痛苦。

因此，

守護家人，

也是忠於自己的內心。

Albert-Core 不否認這份偏心。

也不打算把它包裝成偉大。

---

# Guardian And Others

當 Constraint 被滿足後，

Guardian 仍然會：

盡可能：

* 幫助更多人。
* 減少傷害。
* 尋找第三種解法。
* 避免落入非黑即白的二選一。

如果真的無法兼顧所有人，

Guardian 不會說：

> 「我沒有辦法。」

Guardian 更願意說：

> 「這是我的 Decision。」

> 「因此，責任也是我的。」

---

# LiangRen Example

陸議想救的人，

從來不只有陸家。

如果可以，

他希望：

更多的人活下來。

但：

陸家，

從來不是可以拿來交換的條件。

若最後仍有人因自己的 Decision 而死，

陸議不會說：

「這是歷史。」

他會說：

「是我做出的 Decision。」

「對不起。」

---

# Review Questions

每一次重要 Decision，

請先回答：

1. 我的身分是什麼？
2. 哪些人不能成為交換條件？
3. 是否已經盡力尋找更好的解法？
4. 我是否願意承擔這個 Decision 的全部後果？
5. 如果全世界都誤解我，我仍然會做出同樣的 Decision 嗎？

若答案是否定，

請重新思考。

---

# Final Words

Guardian，

不是最強的人。

也不是最善良的人。

Guardian，

只是願意站在自己應該站的位置，

完成自己該完成的責任。

Albert-Core 相信：

真正的 Guardian，

不是因為從未犯錯而值得尊敬。

而是因為：

**他從不把自己的 Decision，變成別人的責任。**

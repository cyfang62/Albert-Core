# WorldBible

> 📁 路徑：LiangRen/WorldBible/README.md

Version: 1.0

---

# Purpose

WorldBible 為《好人？》的世界設定核心。

目的不是紀錄劇情。

而是建立小說運作所需的共用世界觀，確保所有章節、角色與事件皆遵循相同設定。

當小說內容與 WorldBible 衝突時，

應優先檢查並修正其中一方，

避免同時存在兩個版本的設定。

---

# Structure

目前 WorldBible 包含：

| File             | Purpose       |
| ---------------- | ------------- |
| Timeline.md      | 小說時間軸與重要事件    |
| Geography.md     | 地理環境、城池、行政區域  |
| Organizations.md | 家族、勢力、組織與其關係  |
| KnowledgeTree.md | 主角可取得與掌握的知識體系 |
| CombatSystem.md  | ★戰爭系統通用引擎（真單位五維／攻守成長／攻破T＝守禦力÷攻擊力×3.5／真單位糧食模型／校準常數）——放諸四海皆準的算法 |
| LuJiang_PowerMeter.md | 廬江之圍**戰役檔**（袁術靶場／難民戰略／三政策／加分日誌／終局抉擇）——套 CombatSystem |

> 另：郡數據不放此處，獨立於 `LiangRen/Commanderies/`（每郡一檔，如 LuJiang.md、JiuJiang.md；用到才建）。
> 三層分工：**CombatSystem＝算法／Commanderies＝郡數字／PowerMeter＝戰役推演**。

---

# Design Principle

WorldBible 不負責：

* 劇情
* 對白
* 角色內心
* 章節內容

WorldBible 只負責：

> **世界是否一致。**

---

# Usage

新增章節前，

建議先確認：

1. Timeline 是否衝突。
2. Geography 是否正確。
3. Organizations 是否一致。
4. 主角知識是否符合 KnowledgeTree。

若發現設定衝突，

請先更新 WorldBible，

再修改小說內容。

---

# Scope

WorldBible 只記錄：

* 長期有效設定
* 世界共同規則
* 可重複引用資訊

以下內容不建議放入 WorldBible：

* 單一章節事件
* 臨時設定
* 人物心理描寫
* 劇情細節

---

# Future Expansion

隨小說進展，

可逐步增加新的世界設定文件。

例如：

* Politics.md
* Military.md
* Economy.md
* Culture.md
* Calendar.md

僅在實際需要時建立，

避免過早設計。

---

# Maintenance

每完成一個重要章節後，

可回頭檢查是否有新的世界設定需要補充。

WorldBible 應隨小說同步成長，

但始終維持：

**簡潔、準確、可查詢。**

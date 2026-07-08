# Characters

> 📁 路徑：LiangRen/Characters/README.md

Version: 1.0

---

# Purpose

本資料夾存放《良人》所有已確認身份角色的資料。

每位角色皆使用獨立 Markdown 文件維護。

目的不是紀錄劇情，

而是建立角色的長期設定，確保人物描寫在整部小說中保持一致。

---

# Directory Structure

**扁平化（v2.0改）：所有角色檔直接放在 `Characters/` 底下，不分姓氏/勢力子資料夾。**

原因：單人資料夾＝沒有分類效果的分類，徒增層級。檔名皆帶姓氏前綴（LuYi、LuKang、GuYong、ChenWen…），
排序時同姓自然相鄰，等於「按一下就把同姓氏放一起」，不需靠資料夾分群。

```text
Characters/
├── CharacterIndex.md
├── README.md
├── LuYi.md  LuKang.md  LuJun.md … （陸系·同姓自然相鄰）
├── ChenWen.md  ChenManager.md    （陳·同姓相鄰）
├── FuQian.md  FuBo.md            （服/福）
├── SunCe.md  ZhouYu.md  YuanShu.md  ZhuHuan.md  GuYong.md  ZhangYun.md …
└── （新角色一律直接放這層）
```

勢力/陣營歸屬**寫在各角色檔內文**（Basic Information／Relationship），不靠資料夾表達——因為陣營會隨劇情變動，用資料夾綁死反而易亂。

---

# Character Creation Rule

建立角色檔案需符合：

**身份已確認（Identity Confirmed）**

而不是：

* 是否重要
* 是否有台詞
* 是否出現一次

例如：

建立：

* 陸議
* 陸康
* 福伯
* 陳管事

不建立：

* 黑衣人
* 神秘老人
* 未揭露身份的族老
* 路人甲

待身份正式揭露後，

再建立角色檔案。

---

# Character File Naming

每位角色使用一個獨立檔案。

命名規則：

```text
EnglishPinyin.md
```

例如：

```text
LuYi.md
LuKang.md
FuBo.md
ChenManager.md
```

命名保持一致，

避免後續引用混亂。

---

# Character Template

每個角色檔案建議包含：

* Basic Information
* Current Status
* Timeline
* Relationship
* Personality
* Decision Style
* Ability
* Major Events
* Novel Appearance
* Notes

可依角色重要程度增減內容。

---

# Relationship With WorldBible

Characters 負責：

> **人物本身。**

WorldBible 負責：

* Timeline
* Geography
* Organizations
* Knowledge Tree

若角色涉及：

家族、

勢力、

時間、

地點，

請同步更新對應的 WorldBible 文件。

---

# Maintenance

新增角色時，

請確認：

* 身份是否已確認。
* 是否已有相同角色。
* 是否符合故事設定。
* 直接放在 Characters/ 底下（扁平化·不分子資料夾）；陣營歸屬寫在內文。

角色資料應隨小說進度持續補充，

但避免加入尚未公開或尚未發生的劇情內容。

---

# Goal

Characters 的目標是：

建立一份完整且一致的人物資料庫。

讓任何閱讀《良人》的人，

或任何協助創作的 AI，

都能快速理解每位角色的身份、關係與定位，

並保持角色描寫的一致性。

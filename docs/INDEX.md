Documentation Index

Mahjong Three Kingdom TD

Last Updated: 2026

---

Purpose

This file serves as the master navigation index for all project documentation.

Read order:

README.md
→ docs/INDEX.md
→ System Documents

For AI agents:

README.md
→ docs/INDEX.md
→ STYLE.md
→ AGENTS.md
→ Target Document

---

1. Foundation

Core project documents.

Document| Purpose
麻將塔防遊戲企劃 v10/v20/v30| Project evolution history
Notes| General design notes
README.md| Project overview

---

2. Home System

Player home, faction hub, and progression systems.

Document
主君設計
主君UI
主城堡系統

Related Systems:

- Faction Selection
- Home Navigation
- Main Progression

---

3. Battle System

Core gameplay loop.

Document
戰鬥UI
勝負系統
Events
評價結算系統
Path System（移動規則校正版）

Related Systems:

- Tower Defense
- Combat Loop
- Stage Flow

---

4. Hero System

Playable hero content.

Document
30武將設定
武將基本數值
武將倍率
武將普攻設定

Kingdom Skill Tables:

Document
魏國武將技能表
蜀國武將技能表
吳國武將技能表

Destiny Skills:

Document
曹操的天命技能
劉備的天命技能
孫權天命技能

---

5. Soldier System

Player-controlled military units.

Document
小兵公式
小兵升級系統
小兵AI模式
小兵UI

Related Systems:

- Infantry
- Archer
- Cavalry

---

6. Economy System

Resource generation and spending.

Document
金幣經濟模式
金幣消耗模式
鳴金+Wave設定

Related Systems:

- Gold Economy
- Upgrade Economy
- Wave Rewards

---

7. Stage System

Campaign and progression.

Document
麻將50關
Boss型 × 50關（正式）
關卡模板 × Wave × Story × 章節
關卡與軍隊對應
難度曲線
場上人口設計

Related Systems:

- Campaign
- Difficulty Progression
- Stage Scaling

---

8. Enemy System

Enemy-side content.

Document
敵類型

Related Systems:

- Yellow Turban
- Bandits
- Warlords
- Elite Units

---

9. Formula System

Core numerical framework.

Document
基礎公式

Related Systems:

- Damage
- HP
- Scaling
- Economy

---

10. Art Production Pipeline

Location:

/art/

Core Files:

File
STYLE.md
AGENTS.md

Production Components:

Folder
queue/
prompts/
mahjong/
heroes/
soldiers/
enemies/
boss/
maps/
ui/
fx/

Purpose:

Specification-driven AI asset production.

---

11. Current Production Priorities

Priority A:

- Mahjong Tiles
- Maps
- Home UI

Priority B:

- Heroes
- Soldiers
- Enemies

Priority C:

- Bosses
- FX
- Marketing Assets

---

Source of Truth

Game Design:
docs/

Art Direction:
art/STYLE.md

Production Rules:
art/AGENTS.md

This file is the official documentation navigation hub.

Mahjong Three Kingdom TD

Single Player Mahjong × Three Kingdoms × Tower Defense

---

Project Overview

Mahjong Three Kingdom TD is a single-player strategy game combining:

- Mahjong
- Three Kingdoms heroes
- Tower Defense
- Chibi military fantasy

The project follows a specification-driven workflow.

All systems, assets, and automation pipelines are generated from repository specifications.

---

Repository Structure

Documentation

/docs/

Contains game design documents.

Examples:

- Battle System
- Character System
- Events
- Home UI
- Maps
- Boss Design
- Win/Lose System

---

Art Pipeline

/art/

Contains all AI-assisted asset production workflows.

Core Files

/art/STYLE.md

Visual style foundation.

Defines:

- Art direction
- UI language
- Faction colors
- Mahjong style
- Rendering rules

---

/art/AGENTS.md

Production workflow rules.

Defines:

- Codex behavior
- Queue workflow
- Asset naming
- Validation rules

---

Prompt Library

/art/prompts/

Reusable generation templates.

Examples:

- Mahjong
- Heroes
- Soldiers
- Enemies
- Maps
- UI
- FX

---

Production Queue

/art/queue/

Asset generation task lists.

Examples:

- mahjong_queue.json
- hero_queue.json
- map_queue.json

---

Asset Library

/art/mahjong/
/art/heroes/
/art/soldiers/
/art/enemies/
/art/boss/
/art/maps/
/art/ui/
/art/fx/

Generated production assets.

---

AI Workflow

Production pipeline:

STYLE.md
→ AGENTS.md
→ Queue
→ Prompt Template
→ Asset Generation

All generated assets must follow STYLE.md.

---

Current Production Priority

Phase 1:

- Mahjong Tiles
- Maps
- UI Foundation

Phase 2:

- Heroes
- Soldiers
- Enemies

Phase 3:

- Bosses
- FX
- Marketing Assets

---

Design Principles

- Mobile Landscape First
- Readability First
- Chibi Strategy Fantasy
- Cute Premium Visual Style
- Transparent PNG Production Assets
- Specification Driven Development

---

Source of Truth

System Rules:
/docs/

Art Rules:
/art/STYLE.md

Production Rules:
/art/AGENTS.md

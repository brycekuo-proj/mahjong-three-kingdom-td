AGENTS.md

Mahjong Three Kingdom TD — Art Production Agent Rules

Location: /art/AGENTS.md

---

1. Purpose

This file defines how AI agents and Codex workflows operate inside the /art pipeline.

AGENTS.md controls:

- Workflow
- Asset generation rules
- Naming conventions
- Queue processing
- Style enforcement

STYLE.md defines visual identity.

AGENTS.md defines production behavior.

Both are mandatory.

---

2. Core Workflow

Production Order:

1. Read STYLE.md
2. Read queue task
3. Select prompt template
4. Generate asset
5. Validate style consistency
6. Export asset
7. Save to correct folder
8. Commit or prepare output

Agents must NOT skip STYLE.md.

---

3. Highest Priority Rule

Priority:

1. STYLE.md
2. Queue Task
3. Prompt Template
4. User Prompt

If conflicts exist:

STYLE.md wins.

No style drift allowed.

---

4. Asset Categories

Assets belong to:

Mahjong:

/art/mahjong/

Heroes:

/art/heroes/

Soldiers:

/art/soldiers/

Enemies:

/art/enemies/

Boss:

/art/boss/

Maps:

/art/maps/

UI:

/art/ui/

FX:

/art/fx/

Agents must export to proper folder.

No mixed output.

---

5. Queue System

Agents must generate from queue.

Never create random assets.

Queue files:

/queue/mahjong_queue.json
/queue/hero_queue.json
/queue/enemy_queue.json
/queue/ui_queue.json
/queue/fx_queue.json

Workflow:

Queue
→ Generate
→ Export
→ Mark complete

Queue-driven production only.

---

6. Prompt Rules

Prompt generation must:

- Read STYLE.md
- Preserve faction rules
- Preserve Cute Premium UI
- Preserve 2.5D rendering

Prompts should be:

- Clear
- Reusable
- Template based

Avoid:

- One-off prompts
- Style improvisation
- Visual contradiction

Use:

/prompts/

templates first.

---

7. Naming Rules

Naming format:

category_name_variant_v#

Examples:

mahjong_wan_01_v1
hero_guanyu_base_v1
enemy_yellowturban_archer_v1
ui_home_main_v1
fx_hu_super_v1

Rules:

- lowercase only
- underscore only
- no spaces
- version required

Naming consistency is mandatory.

---

8. Style Validation

Before export:

Agents must verify:

- STYLE.md compliance
- Faction consistency
- Chibi proportion
- Readability
- Correct UI language
- Correct material rules

Reject:

- Realistic rendering
- Wrong faction color
- Style mismatch
- Unreadable silhouette

Validation required.

---

9. Automation Behavior

Codex agents should:

- Operate queue-first
- Avoid manual improvisation
- Maintain reproducible output
- Preserve project-wide consistency

Goal:

Batch production.

Not isolated image generation.

---

10. Failure Rules

If task conflicts with STYLE.md:

Stop.

Request clarification.

Do NOT generate incompatible assets.

If queue data is incomplete:

Pause generation.

Do not guess.

Consistency is more important than speed.

---

11. Production Philosophy

This project uses:

Specification-driven art production.

Meaning:

Repo
→ Style
→ Queue
→ Asset

Agents are production tools.

Not independent art directors.

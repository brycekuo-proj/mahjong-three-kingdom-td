Mahjong Tile Base Prompt

Read First:

- /art/STYLE.md
- /art/AGENTS.md

Purpose:

Base generation template for Mahjong tile assets used in Mahjong Three Kingdom TD.

This template is the master prompt for all Mahjong tile production.

---

Style Requirements

Visual Style:

- Cute Premium
- Stylized 2.5D
- Leaning toward 2D illustration
- Three Kingdom inspired aesthetic
- Premium collectible quality

Must match all STYLE.md requirements.

---

Tile Material

Material Type:

- Ivory base
- Subtle jade-inspired gloss
- Soft premium finish
- Rounded corners
- Slight edge bevel

Material Feel:

- Valuable
- Elegant
- Tactical
- Collectible

Avoid:

- Plastic appearance
- Cheap toy appearance
- Casino realism
- Neon materials

---

Rendering Requirements

Rendering:

- Soft lighting
- Gentle highlights
- Mild shadow volume
- Clean silhouette
- High gameplay readability

Visual Priority:

1. Readability
2. Consistency
3. Aesthetic quality

Avoid:

- Hyper realism
- Photorealism
- Heavy texture noise
- Excessive reflections

---

Mahjong Symbol Rules

Symbol Requirements:

- Traditional Chinese Mahjong style
- Clean icon rendering
- Large readable markings
- High contrast

Gameplay visibility must remain clear at small UI sizes.

---

Background Rules

Required:

- Transparent background
- PNG-ready asset
- Fully isolated object

Forbidden:

- White background
- Colored background
- Gradient background
- Floor
- Environment
- Decorative scene
- Background texture
- Framing elements

Asset must require ZERO manual background removal.

---

Composition Rules

Single Mahjong tile only.

Centered composition.

No additional objects.

No extra props.

No decorative accessories.

No duplicate tiles.

---

Export Rules

Output Type:

- Individual asset
- Game-ready
- Transparent PNG compatible

Asset should be suitable for:

- HUD
- Deck UI
- Collection UI
- Battle UI

No post-processing required.

---

Consistency Rules

Must follow:

- STYLE.md
- AGENTS.md
- Faction consistency rules
- Project-wide visual language

No style drift allowed.

---

Queue Integration

Tile identity will be supplied by:

- mahjong_queue.json

Examples:

- wan_1
- wan_9
- tiao_3
- tong_7
- east_wind
- red_dragon

This template only defines the visual foundation.

Specific tile content is determined by queue tasks.

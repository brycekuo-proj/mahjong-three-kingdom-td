Map Base Prompt

Read First:

- /art/STYLE.md
- /art/AGENTS.md

Purpose:

Base generation template for stage map assets used in Mahjong Three Kingdom TD.

This template defines the visual foundation for tower defense battlefield maps.
Specific map theme, faction influence, terrain features, and chapter identity must come from queue tasks.

---

Style Requirements

Visual Style:

- Cute Premium
- Stylized 2.5D
- Leaning toward 2D illustration
- Three Kingdom inspired battlefield atmosphere
- Warm tactical readability

Must match all STYLE.md requirements.

---

Map Format Rules

Required:

- 16:9 landscape composition
- Suitable for mobile landscape, tablet landscape, and PC landscape
- Built for tower defense stage layout readability
- Clear usable space for lane and path design

Map must support:

- Enemy path readability
- Tower or unit placement readability
- Spawn and goal clarity
- Combat visibility

Avoid:

- Portrait composition
- Square composition
- Overly cinematic crop
- Layouts that hide routes or stage logic

---

Battlefield Style

Environment Direction:

- Cute war map
- Stylized terrain
- Warm atmosphere
- Low clutter
- Strong lane readability

Avoid:

- Dense environmental noise
- Realistic terrain simulation
- Dark grim warfields
- Excessive ruins or destruction clutter

Combat readability is prioritized over realism.

---

Rendering Requirements

Rendering:

- Soft lighting
- Mild shadow volume
- Clean value separation
- Readable ground shapes
- Clear path structure

Avoid:

- Photorealism
- Heavy texture noise
- Excessive particles
- Overly dramatic fog or bloom

---

Composition Rules

- Landscape stage overview
- Clear navigable battlefield layout
- Space for enemy lanes and tactical interaction
- Focal landmarks may exist, but must not break readability

Recommended content:

- Roads or paths
- Terrain zones
- Fortified structures
- Faction-flavored props
- Clean gameplay landmarks

Avoid:

- Decorative composition with no gameplay logic
- Overlapping paths that are hard to parse
- Extreme perspective distortion

---

Background Rules

Map assets do not require transparent background.

Required:

- Full scene composition
- Complete battlefield image
- Clean stage boundaries

Forbidden:

- Transparent cutout map output
- Empty floating terrain fragments

---

Export Rules

Output Type:

- Individual map asset
- Game-ready
- 16:9 landscape stage image

Asset should be suitable for:

- Stage background
- Tactical battlefield layout
- Chapter progression maps

No post-processing required.

---

Consistency Rules

Must follow:

- STYLE.md
- AGENTS.md
- Faction consistency rules
- Gameplay readability rules
- Project-wide visual language

No style drift allowed.

---

Queue Integration

Map identity will be supplied by queue tasks.

Examples:

- map_yellowturban_plains_v1
- map_wu_riverfront_v1
- map_shu_mountain_pass_v1

This template only defines the visual foundation.

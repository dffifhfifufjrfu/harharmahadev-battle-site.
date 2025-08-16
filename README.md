# HarHarMahadev_Battle — Asset Creation & Pre-Launch Pack

Hi partner 👋 — this pack contains templates, checklists, and a tiny example sprite to help you create and document your game assets **using only free tools** (as requested).

---
## What I included
- `Docs/dev_log.txt` — editable dev log template with examples.
- `Docs/license_checklist.md` — step-by-step pre-launch copyright checklist.
- `README.md` — this file (you’re reading it).
- `Assets/Sprites/example_sprite.png` — a tiny example 32x32 sprite you can replace.
- Folder placeholders: `Assets/Models/`, `Assets/Music/`, `Assets/Sprites/`

---
## Tools (free) — quick guide
- **Sprites**: Pixilart (draw in browser) — export as PNG (recommended sizes: 32×32, 64×64, 256×256 for UI). Name files `sprite_<name>_v1.png`.
- **3D Models**: Blender (free). Use **Chola sculpture** references for style inspiration (search "Chola bronze Nataraja", "Chola dynasty sculpture") and model in Blender. Export to `.glb`/`.gltf` for web/Unity or `.fbx` for Unity workflows.
- **Music**: Audacity (recording/edit). Use free VST plugins (example: "Ancient Veena VST" — or any free sitar/veena VST). Export WAV (44.1kHz / 16-bit) for best compatibility; create OGG for smaller size.
- **License Tracking**: Always keep a `license.txt` or `assetname_license.txt` with each asset describing source, author, license (link), and date acquired.

---
## Quick workflow examples
### Sprite (Pixilart)
1. Open Pixilart, draw 32×32 or 64×64 canvas.
2. Export → PNG → Save in `Assets/Sprites/` as `sprite_<name>_v1.png`.
3. Create `Assets/Sprites/sprite_<name>_license.txt` containing author/source/license/date.

### 3D Model (Blender → Unity)
1. Model using references; avoid copying copyrighted sculpture photos directly — use them as reference only.
2. Retopologize, unwrap UVs, bake normal/ao maps if needed.
3. Export: `File → Export → glTF 2.0 (.glb/.gltf)` for web or `.fbx` for Unity.
4. Put model + `modelname_license.txt` in `Assets/Models/`.

### Music (Audacity + VST)
1. Record or program melody in Audacity or a free DAW. Use free VSTs for instruments.
2. Export WAV (44.1 kHz) or OGG for in-game use.
3. Put file + `trackname_license.txt` in `Assets/Music/`.

---
## Dev log format (use Docs/dev_log.txt)
Always add new lines at top. Include timestamps like:
[YYYY-MM-DD HH:MM IST] <action> — author/credit

Example:
[2025-07-23 14:12 IST] Implemented pistol damage system; original mechanic by Shiv Gupta
[2025-07-24 09:00 IST] Created "Tejas" token system - original mechanic by Shiv Gupta

---
## Pre-launch checklist (Docs/license_checklist.md)
Follow this checklist before you publish. Keep evidence (screenshots, receipts, URLs).

1. Run **WIPO Global Brand Database** search for `HarHarMahadev_Battle` — save screenshot of results.
2. In Unity, run **Asset Usage Detector**/Asset Detective and export a list of all used assets.
3. For each third-party asset found:
   - If license is **Commercial** or **Royalty-free for commercial**, keep it and save proof.
   - If license is **Free for non-commercial only**, replace it immediately.
   - If license is unclear, remove/replace or get written permission.
4. Create `Docs/assets_license_manifest.json` listing each asset and license info. (Template included.)
5. Keep all original creation files (Blender `.blend`, Audacity `.aup3`) in a separate backup folder.
6. Final check: prepare a ZIP of `Docs/`, `Assets/` and evidence, and give it to your legal reviewer / me for cross-checking.

---
If you want, I can:
- Replace the example sprite with real sprites you draw or upload.
- Create Blender starter scenes or a sample `.glb` mockup inspired by Chola style (I will make sure it's original).
- Fill `Docs/assets_license_manifest.json` with entries you provide so it’s ready for audit.

Tell me which of these you want me to do next and I’ll prepare another ZIP. 🙌

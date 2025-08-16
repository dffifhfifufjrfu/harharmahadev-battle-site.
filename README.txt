HarHarMahadev_Battle — Asset Pack (Template)
===========================================

This ZIP is a *template* folder structure for your complete game assets.
Replace the placeholders with your real files, then recompress as a single ZIP.

Created: 2025-08-14T12:02:14.497381

What’s inside
-------------
- Audio/ — music (BGM) and sound effects (SFX)
- Textures/ — all images & atlases (characters, environment, UI)
- Models/ — FBX/OBJ/etc. 3D models
- Animations/ — .anim/.fbx animation clips
- Shaders/Materials/ — .shadergraph, .shader, .mat
- Prefabs/ — Unity prefabs for weapons, characters, props
- UI/ — sprites, fonts, icons
- Scenes/ — .unity scenes (if you have the project)
- Scripts/ — .cs source code
- VFX/ — particle systems, textures
- Addressables/ & Bundles/ — exported asset bundles
- Docs/ — design docs, notes
- Licenses/ — third-party licenses

How to extract real assets from your APK (phone only)
-----------------------------------------------------
1) Export your APK
   - Install "APK Exporter" from Play Store
   - Export your game’s APK to Downloads

2) Extract Unity asset files
   - Install "MT Manager" (search online for APK)
   - Open your APK in MT Manager
   - Go to: assets/bin/Data/
   - Copy all files ending with: .assets, .resource, .resS, .bundle, globalgamemanagers, level* to a new folder

3) Convert to usable files (textures, audio, models)
   - BEST: Use a PC tool "AssetRipper" or "Unity Asset Studio": Open the extracted files -> Export
   - PHONE-ONLY: You can preview/extract some textures/audio with MT Manager, but 3D models export is limited

4) Drop exported files into this template
   - Textures -> Textures/*
   - Audio -> Audio/*
   - Models -> Models/*
   - Animations -> Animations/*
   - etc.

5) Zip the folder
   - On Android use "ZArchiver": long-press the folder -> "Compress" -> ZIP

Notes
-----
• This template does NOT contain your actual proprietary assets. You must extract and place them here.
• Keep third‑party content licenses in /Licenses.
• If using Addressables/Bundles in Unity, place built bundles in /Addressables or /Bundles.
# Cyborg Chess – game assets

This repository holds the 3D models, audio and UI images used by **Cyborg Chess**, my entry for the
Base44 x Nitro Web Game Contest.

- **Game (built in Base44):** https://analytic-model-mesh-mate.base44.app/
- **Author / owner:** KaivanETH. This repository and the Base44 app belong to the same person.
- **Why the assets are here:** Base44 loads 3D models from a public URL, so the GLB, audio and image files are
  hosted here and served via jsDelivr. The game itself (all game code, rules, UI and menus) was built
  inside the Base44 editor, starting 2026-11-20. No code or template was imported from another game project.
- The game uses the frozen release tag **v1.0**.

## Where every asset comes from

All assets were made from scratch for this game. None were downloaded from asset stores or other games.

| Asset | How it was made | Licence / permission |
|---|---|---|
| 7 character models (`models/`) | Original characters. Concept images generated from my own text prompts with FLUX.1-schnell, turned into 3D with Hunyuan3D-2, then cleaned up, recoloured, rigged and hand-animated in Blender | FLUX.1-schnell: Apache 2.0. Hunyuan3D-2: Tencent Hunyuan 3D 2.0 Community License (commercial use allowed; I am outside the excluded territories) |
| City, board and terrain models | Built with my own Blender Python scripts | My own work |
| UI portraits and terrain icons (`ui/`) | Blender renders of my own models | My own work |
| Character voices and announcer (`audio/voice/`) | ElevenLabs Voice Design (synthetic voices, not based on any real person) | ElevenLabs Creator plan, commercial use allowed |
| Music and sound effects (`audio/`) | ElevenLabs music and sound effects | ElevenLabs Creator plan, commercial use allowed |
| Fonts (loaded by the game) | Google Fonts, e.g. Lilita One | SIL Open Font License |
| Code libraries (used by the game) | three.js with GLTFLoader, DRACOLoader, SkeletonUtils | MIT |

**Making-of proof:** the [`provenance/`](provenance/) folder shows each character in three steps:
concept image, then raw image-to-3D output, then the final model used in the game. I keep the raw source files
(prompts, raw meshes, .blend files) privately and can share them with the contest organisers on request.

**AI assistance:** I used Claude (Anthropic's AI assistant) to help write the game-design specs that I
gave to the Base44 AI builder, and to write the Blender scripts that made the assets above. Under Anthropic's
terms, the output belongs to me. No code from Claude was imported into the game as a separate project. The game
code was generated and iterated inside Base44.

## Licence

© 2026 KaivanETH. All rights reserved. These assets may only be used in Cyborg Chess.

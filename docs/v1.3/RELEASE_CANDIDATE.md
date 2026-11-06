# Christmas Lights v1.3.0-rc.1 — preparation 🎄

**Status: RELEASE CANDIDATE — NOT A STABLE OR VERIFIED BINARY.** The existing [v1.0.0 release](https://github.com/Horizongit228/ChristmasLights/releases/tag/v1.0.0) remains the published Windows download.

## What's new compared with v1.0

- Aurora UI with a redesigned dark settings panel and custom color picker.
- Audio Wave 3.0 with approved fixed music response, Classic fallback for video/fullscreen, and improved rhythm detection.
- LightCast with a fixed one-layer, 10% halo profile.
- CL Studio: individual bulb painting and shapes, ordered gradients, color presets and patterns, symmetry, undo/redo, per-color brightness and saturation, and JSON designs.
- Infinity Garland: overlays on multiple monitors, shared audio capture, continuous wave routing and continuous directional running colors; single-monitor waves still start in the middle.
- Wallpaper-derived palettes and improved lighting animations (breathing, flicker, wave and sparkles).
- Candidate safeguard: backup/recovery of JSON settings and designs.

## Prerequisites for publishing

1. Upload candidate source from the prepared package to the `release/v1.3-preparation` branch after choosing a source license.
2. Run the Windows build + all current C# regression tests, with zero errors.
3. Test real Windows 10/11, multiple DPI settings, fullscreen video/games, audio devices, save/reload and CL Studio.
4. Create portable EXE and installer from the **same verified commit**; compute and verify SHA-256.
5. Publish as a **prerelease** first; only publish stable `v1.3.0` after the release checklist is complete.

**No EXE is attached here.** A source ZIP is not a compiled app. Full notes and workflow templates are in the candidate source package. The public v1.0.0 release must not be modified or deleted.

---
Русский: это подготовка v1.3, а не готовый стабильный выпуск. Не публикуйте ссылку для пользователей TikTok до успешной Windows-сборки и испытаний.

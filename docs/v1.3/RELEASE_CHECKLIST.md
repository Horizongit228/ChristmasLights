# v1.3 release gate — Windows verification

- [ ] Restore NuGet dependencies and run the .NET 10 **WPF Release build** without errors.
- [ ] Run all 4 current C# test suites: CoreChecks, LightingModesRegression, AudioWaveFastRegression, SmartAudioRegression.
- [ ] Validate the new source preflight and AW3/LightCast source hashes.
- [ ] Verify old v1.0 settings, saved CL Studio designs, JSON import/export and recovered .bak backups.
- [ ] Try all lighting modes with Audio Wave **off**; verify the glass visibly animates.
- [ ] Test Audio Wave 3.0 on music and silence; confirm Classic fallback for video and genuine fullscreen.
- [ ] Check one monitor (waves from center) and 2+ monitors (continuous wave and directional running colors).
- [ ] Test fullscreen visibility, monitor hotplug, negative coordinates and mixed DPI.
- [ ] Try LightCast, one layer, halo 10%, and disabling it for fullscreen.
- [ ] Check tray startup/exit and no duplicate application instances.
- [ ] Test portable EXE and installer on a clean Windows 10/11 PC; check install/uninstall/shortcuts.
- [ ] Check SHA-256 of final EXE and installer, verify SmartScreen behavior and note unsigned status honestly.
- [ ] Select source-code license before publishing source; review third-party notices.
- [ ] Prepare real screenshots captured from the **candidate**, not old v1.0 or mockups.
- [ ] Promote to stable only after these items are complete.

Do not touch existing v1.0 release assets. The release workflows must **never automatically publish binaries**.

# X1360 — Android Xbox 360 emulator build

This repository builds the open-source **Xendroid+** Android Xbox 360 emulator from its upstream source. It is an emulator build, not a native GTA V port.

## Build an APK

Open **Actions → Build X1360 Android APK**. The workflow checks out a pinned Xendroid+ source revision, compiles the arm64 Android APK, and uploads it as a workflow artifact.

## Device and game notes

- Target: Android arm64 + Vulkan; Snapdragon/Adreno devices are the intended focus.
- Add your own legally dumped Xbox 360 game files through the emulator's game-folder picker. GOD package support is provided by the emulator; keep the package's full folder structure intact.
- GTA V on Android is experimental. A successful APK build does **not** prove GTA V will boot or run smoothly on a particular phone. The Snapdragon 8+ Gen 1 / Adreno 730 is below Xendroid+'s recommended Snapdragon 8 Gen 2 / Adreno 740 class, so stable high frame rates cannot be promised.
- Game files, console firmware, keys and copyrighted game assets are not included.

## Upstream and license

- Upstream source: https://github.com/phforner0/Xendroid-Plus
- Build instructions and third-party notices are maintained upstream. Xendroid+ is licensed under AGPL-3.0-or-later; Xenia and bundled dependencies retain their own licenses. See the upstream repository for the complete notices.

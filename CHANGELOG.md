# Changelog

## 1.0.1
- Manual-install zips for players who set up BepInEx themselves: `-with-BepInEx` (includes BepInEx 5.4.23.5) and
  `-plugin-only` (for an existing BepInEx 5 install). Instructions in `README-MANUAL.txt`.
- Umm Mod Launcher: new command-line mode `--enable-vr` / `--disable-vr` that only switches Unity's VR support on or
  off in the game data (with a backup), for manual installs.

## 1.0.0
First public release.
- Full game in PC VR via SteamVR: stereo 3D, head tracking, layered 3D main menu.
- Motion controls: hand-aimed weapon with a smoothed aim ray, point-and-grip interaction, thumbstick movement,
  snap or smooth turning, laser pointer for menus.
- Head-locked VR HUD; enemy names, health bars and damage numbers in the world.
- Comic ink outlines matched to the flat game.
- SteamVR Input with default controls for Quest/Touch, Index, Steam Frame, Vive and Windows Mixed Reality,
  plus left-handed layouts; rebind anything in SteamVR.
- Umm Mod Launcher: checks your PC, installs with backups, launches in VR, repairs after game updates,
  restores the original game.
- Tested on the Epic Games Store version with a Meta Quest 3 via Virtual Desktop.

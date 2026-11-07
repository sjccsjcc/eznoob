# eznoob - Nexomia Edition

This repository contains the **Nexomia Edition** of the Vape client (Roblox script hub).

The full source pack was provided as `nexomiaedition.7z` (693 files).

## Structure

- `newvape/` - Main client folder
  - `main.lua` / `loader.lua` - Entry points
  - `games/` - Per-game modules (BedWars, SkyWars, BlockWars, etc.)
  - `guis/` - Different GUI themes (new, liquidbounce, moon3, autumnv1, rise, wurst...)
  - `libraries/` - Shared libraries (entity, drawing, prediction, etc.)
  - `profiles/` - Configs and profiles
  - `assets/` - GUI assets (images, fonts)

## Note

Due to the large number of files (including ~190 binary PNG/TTF assets), a full automatic upload of every file is limited in this chat interface.

I can upload the core Lua files and structure on request. For the complete pack, download the original `.7z` from the chat and extract it into this repo, or tell me which specific folders/files to prioritize.

To use: place the `newvape` folder in your executor workspace and run `loader.lua`.

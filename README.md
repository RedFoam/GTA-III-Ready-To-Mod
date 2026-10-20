# GTA III — Ready to Mod 🌆

**A simpler way to set up Grand Theft Auto III Classic on modern Windows PCs.**

This project brings essential fixes, controller support, widescreen improvements, and modding tools together in one convenient place. The goal is to help players spend less time searching across websites and more time enjoying Liberty City.

**Game target:** Classic PC retail v1.0

## 🔗 Working on the Other Classic GTA?

- 🌴 [GTA Vice City — Ready to Mod](https://github.com/RedFoam/Grand-Theft-Auto-Vice-City-ready-to-mod)

Looking for the other classic GTA setup? Check out the companion project!

## 📌 Game Version — Retail v1.0 Included

The **GTA III retail v1.0 executable (`gta3.exe`) is included in this pack** for compatibility with the intended classic-PC setup.

Want the original download separately, or need to keep another copy?

- **[GTA III Original v1.0 EXE — ModDB](https://www.moddb.com/games/grand-theft-auto-3/downloads/grand-theft-auto-3-original-10-exe-for-steam)**

Always back up your original executable before replacing it. This project targets classic GTA III, not Grand Theft Auto: The Trilogy — The Definitive Edition.

## 📦 Included Mods and Components

### 🔧 Essential Fixes and Compatibility

| Component | Purpose | Source |
|---|---|---|
| **SilentPatchIII** | Fixes bugs and improves compatibility with modern Windows systems. | [Silent's Blog](https://silentsblog.com/mods/gta-iii/) · [GitHub](https://github.com/CookiePLMonster/SilentPatch) |
| **GTA III Widescreen Fix** | Improves widescreen and ultrawide support, HUD positioning, field of view, and display compatibility. | [Widescreen Fix releases](https://github.com/ThirteenAG/WidescreenFixesPack/releases/tag/gta3) · [Documentation](https://github.fusionfix.io/wfp#gta3) |
| **GInputIII** | Improves controller support and gamepad input. | [Silent's Blog](https://silentsblog.com/mods/gta-iii/) |
| **VBDec** | Enables native playback of VB-format audio files. | [GitHub](https://github.com/CookiePLMonster/VBdec) |

### 🧰 Modding Tools

| Component | Purpose | Source |
|---|---|---|
| **Mod Loader v0.3.10** | Lets supported mods load from separate folders instead of requiring users to replace original game files manually. | [Official v0.3.10 release](https://github.com/thelink2012/modloader/releases/tag/v0.3.10) |
| **Ultimate ASI Loader** | Loads compatible ASI plugins, including Mod Loader. The correct compatible loader must be installed for the game. | [Official releases](https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases) |

### 🌃 Graphics and Visual Improvements

| Mod | Purpose | Source |
|---|---|---|
| **Project2DFX** | Extends the visibility of distant lights and city details to improve Liberty City's skyline. | [GTA III release](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX/releases/tag/gta3) |

### 🎮 Gameplay and Quality of Life

| Mod | Purpose | Source |
|---|---|---|
| **Money Messages** | Adds money notifications during gameplay. | [Silent's Blog](https://silentsblog.com/mods/gta-iii/) · [GitHub](https://github.com/CookiePLMonster/Money-Messages) |
| **Destroyable Airtrain** | Restores the ability to destroy the airtrain. | [Silent's Blog](https://silentsblog.com/mods/gta-iii/) · [GitHub](https://github.com/CookiePLMonster/Destroyable-Airtrain) |

## 🚀 Installation

The aim is to make setup as straightforward as possible.

1. Download this repository.
2. Back up your original GTA III folder, especially `gta3.exe`, DLL files, and save files.
3. Open the game directory containing `gta3.exe`.
4. Copy the repository's files and folders into the game directory, preserving the included folder structure.
5. If Windows asks to merge folders, check the destination and merge where appropriate.
6. Review file replacement prompts carefully. Do not blindly overwrite DLLs or other existing files.
7. Launch the game and verify it works before making additional changes.

### Mod Loader Installation Layout

GTA III Mod Loader v0.3.10 requires **Ultimate ASI Loader**.

For a standard GTA III installation, the relevant structure is:

```text
GTA III/
├── gta3.exe
├── dinput8.dll              (Ultimate ASI Loader, if using this filename)
├── modloader/
│   └── [individual mod folders]
└── scripts/
    └── modloader.asi
```

The ASI loader's filename may vary according to its configuration. Do not install a second competing loader simply because its filename differs from the example.

Keep `modloader.asi` in `scripts/` and the `modloader/` directory in the game root, as specified by the Mod Loader installation instructions.

### Installing Mods Through Mod Loader

1. Open the game's `modloader/` folder.
2. Create a separate folder for each supported mod.
3. Place the mod's files inside its own folder, preserving the folder structure required by that mod.
4. Launch the game and check that the mod loads correctly.

Mod Loader can simplify installing and removing compatible mods, but it does not eliminate every dependency or guarantee that all mods work together.

## ⚙️ Requirements

- Classic PC Grand Theft Auto III.
- Retail v1.0 executable included in this setup.
- Windows PC.
- Ultimate ASI Loader for Mod Loader and other compatible ASI plugins.
- Any additional dependencies required by individual mods.

## ⚠️ Important Compatibility and Backup Notes

- This pack is intended for classic GTA III, not the Definitive Edition.
- Back up your game files and saves before installing or updating.
- Do not install competing ASI loaders or graphics wrappers without checking compatibility.
- Avoid blindly replacing `dinput8.dll`, `d3d8.dll`, or other loader and wrapper files.
- Preserve the folder structure of the included mods.
- Some mods may require additional configuration or separate dependencies.
- If the game crashes, test the core setup first, then add optional components one at a time.
- The presence of individual mods in this repository does not mean every possible combination has been independently tested.

## ❤️ Credits

Thanks to the developers and contributors who keep classic GTA modding alive, including Silent, CookiePLMonster, ThirteenAG, LINK/2012, and the wider GTA modding community.

Please visit each original project for its documentation, updates, and support.

This is an unofficial community project and is not affiliated with or endorsed by Rockstar Games.

## 📜 Licensing and Distribution

Third-party components remain subject to their original licenses and redistribution terms. The inclusion of a component in this repository does not change its original license.

Where redistribution is not permitted, obtain the component directly from its original source. The ModDB executable link is provided for users who want to access the original download separately.

---

## 🌴 More Classic GTA Mods

Want to set up Vice City instead?

**[Grand Theft Auto: Vice City — Ready to Mod](https://github.com/RedFoam/Grand-Theft-Auto-Vice-City-ready-to-mod)**

The mission is simple: make classic GTA games easier to set up on modern hardware, with useful files and trusted source links in one beginner-friendly place.

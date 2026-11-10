# Retrofit Rights / 改造权

[简体中文](README.md) | **English**

A **Probably Stolen** mod for material-based container expansion and inventory display adjustments. It works independently; Scavenging Expansion is not required.

This repository provides **stable release downloads and issue reporting**. Source code is not published here.

- **[Download the latest stable release](https://github.com/eotn00/ProbablyStolen-RetrofitRights/releases/latest)** — Under Assets, download `RetrofitRights-<version>.zip`, not GitHub's automatically generated Source code archives.
- **[Report a bug in English](https://github.com/eotn00/ProbablyStolen-RetrofitRights/issues/new?template=bug-report.en.yml)** — Describe what happened and attach the `Player.log` from the affected game session.
- [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3833929097)
- [Recommended companion mod: Scavenging Expansion](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/blob/main/README.en.md)

## Installation and updates (Windows)

1. Exit the game and back up your saves.
2. Download the mod ZIP from Releases. Extract its `RetrofitRights` folder into the game's `Mods` directory.
3. Check that the paths are `Mods/RetrofitRights/manifest.xml` and `Mods/RetrofitRights/RetrofitRights.dll`. Avoid an extra nested folder with the same name.
4. Enable the mod in the game's mod menu and restart if prompted. Press **F8** in game to open the menu. See the included `README.txt` for detailed gameplay instructions.

In Steam, use **Manage → Browse local files** to find the game installation directory. Alternatively, subscribe through Steam Workshop.

**Do not keep Workshop, local release, and test copies with the same mod ID installed together.** Back up saves before switching sources, and exit the game before removing duplicate mod copies. When updating a local installation, replace the mod files, not your personal saves.

## Controls and save safety

- Buy a category's retrofit ranks first, then hold **Shift** and drag materials onto a container icon to unlock cells. Dropping items into inventory cells stores them instead. At the dump, submitting without Shift is enabled by default and can be disabled in settings.
- Display adjustments do not change actual capacity. The display module can be used on its own; the expansion module requires the display module.
- **Do not simply uninstall the mod while your save still relies on expanded storage.** Disabling a feature is not the same as uninstalling. See the included documentation for existing capacity, material progress, and Xiaowo migration precautions.
- Material-based expansion of the Inventor Backpack is still handled by Scavenging Expansion. Not every third-party custom container is guaranteed to be compatible.

## Reporting a problem

Search existing Issues first, then use the **[English bug report form](https://github.com/eotn00/ProbablyStolen-RetrofitRights/issues/new?template=bug-report.en.yml)**. A GitHub account is required to submit a report. Include:

- Your game version, mod version, installation source, and other enabled mods.
- What actually happened, what you expected, and the steps leading to the problem. For container problems, specify the container type, page, and relevant settings.
- **The complete `Player.log` from the session in which the problem occurred.** Screenshots or videos are helpful, but do not replace the log.

You do not need to know which mod caused the problem. Describe the symptoms and list the enabled mods.

### Finding Player.log (Windows)

1. Launch the game and reproduce the problem.
2. Press `Win + R`, paste the following path, and press Enter:

   ```text
   %USERPROFILE%\AppData\LocalLow\Questing Goose Studio\Probably Stolen
   ```

3. Immediately copy `Player.log` somewhere safe, then drag it into the form's log field. **Collect it before launching the game again**, as a new session may overwrite it. If relevant, also attach `Player-prev.log` and identify which session it belongs to.
4. If GitHub rejects `.log` files, ZIP the log or rename a copy to `.txt` and upload that instead. Wait for the upload to finish before submitting. Do not provide only a few error lines or a screenshot of the log.

Issues and attachments are public. Check for personal information such as usernames and local paths before uploading. If necessary, redact only sensitive information while keeping the relevant errors and context. Do not upload passwords, tokens, or unrelated personal files. If you cannot obtain the log, explain why and which location you checked in the log field.

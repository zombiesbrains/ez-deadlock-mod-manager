# TODO:

<h2>EZDeadlockModManager.py</h2>

- [ ] FEATURE: Add alphabetical sort for installed mods
- [ ] FEATURE: Remove all mods/turn off mod buttons (either from addons directory or change gameinfo.gi file)
- [ ] FEATURE: Add drag and drop for files straight from file explorer
- [ ] FIX: Need to detect the other rar tools (like 7z.exe) using RAR_TOOL_REGISTRY_PATHS, and find a way on linux (setting the rar tool manually works however)
- [ ] FIX: Make currently selected mod highlight a different colour
- [ ] FEATURE: Add multiple profiles, using multiple settings json files
- [ ] FIX: Rar tool isn't set in settings file when it is detected if blank (unrar is automatically found and works though)

<h2>deadlock_mod_browser.py</h2>

- [ ] FEATURE: Add sort for mods in the browser -> use the _sSort parameter, which has allowed values: new, default, updated
- [ ] FEATURE: Add a page number
- [ ] FIX: Sounds still play after mod browser is closed, we want to close the sound and keep the mod browser object
- [ ] FEATURE: Cache old pages/Preload pages

<h2>deadlock_mod_browser_features.py</h2>

- [ ] FEATURE: Blur the image preview if the visibility is set to False

<h2>settings_window.py</h2>

- [ ] FEATURE: Add a way to delete old download folders if they exist, these should only exist if a user force closes during a download though

<h2>Other</h2>

- [ ] Add screenshots
- [ ] Menu emojis and theme are bugged on Linux
- [ ] Load game button does not work on Linux (requires using subprocess instead)
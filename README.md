<img alt="" src="tray.png" align="right"  height="128px">

**Tray** is an [Obsidian](https://obsidian.md/) plugin that can be used to launch the app
on system startup and run it in the background, adding global hotkeys and a tray menu that
toggle app window visibility and can create quick notes from anywhere in your operating system.

## Configuration

### Window management

| Option                     | Description                                                                                                                                                                                                                        | Default             |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| Launch on startup          | Open Obsidian automatically whenever you log into your computer.                                                                                                                                                                   | Disabled            |
| Hide on launch             | Minimises Obsidian automatically whenever the app is launched. If the "Run in background" option is enabled, windows will be hidden to the system tray/menubar instead of minimised to the taskbar/dock.                           | Disabled            |
| Run in background          | Hide the app and continue to run it in the background instead of quitting it when pressing the window close button or toggle focus hotkey.                                                                                         | Disabled            |
| Hide taskbar icon          | Hides the window's icon from from the dock/taskbar. This may not work on all Linux-based OSes.                                                                                                                                     | Disabled            |
| Create tray icon           | Add an icon to your system tray/menubar to bring hidden Obsidian windows back into focus on click or force a full quit/relaunch of the app through the right-click menu. _Changing this option requires a restart to take effect._ | Enabled             |
| Toggle window focus hotkey | This hotkey is registered globally and will be detected even if Obsidian does not have keyboard focus. Format: [Electron accelerator](https://www.electronjs.org/docs/latest/api/accelerator)                                      | CmdOrCtrl+Shift+Tab |

> **Note**
> The `Relaunch Obsidian` action can be triggered from the tray/menubar context menu, or with the in-app
> command palette (search for "Tray: Relaunch Obsidian"). Hotkeys can be assigned to the command via
> Obsidian's built-in hotkey manager.

### Quick notes

| Option                 | Description                                                                                                                                                                                   | Default           |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| Quick note location    | New quick notes will be placed in this folder.                                                                                                                                                |                   |
| Quick note date format | New quick notes will use a filename of this pattern. Format: [Moment.js format string](https://momentjs.com/docs/#/displaying/format/)                                                        | YYYY-MM-DD        |
| Quick note hotkey      | This hotkey is registered globally and will be detected even if Obsidian does not have keyboard focus. Format: [Electron accelerator](https://www.electronjs.org/docs/latest/api/accelerator) | CmdOrCtrl+Shift+Q |

## Installation

### Obsidian Marketplace (Coming Soon)

1. In Obsidian, navigate to **Settings** → **Community plugins**.
2. Press the **Browse** button beside the **Community plugins** option.
3. Search for `Tray` in the **Filter** text input.
4. Select `Tray` and press **Install**.
5. Once the plugin has finished installing, press **Enable**.
6. Press the **Options** button.
7. Configure the plugin as you wish.
8. You're done! 🎉

### Manual

1. Download this repository.
2. Copy it into your vault's `.obsidian/plugins` directory.
3. In Obsidian, navigate to **Settings** → **Community plugins**.
4. Press **Turn on community plugins** if you haven't already.
5. Find `Tray` in the list of **Installed plugins** and toggle it on.
6. Press the **⚙️** button beside the toggle you just used.
7. Configure the plugin as you wish.
8. You're done! 🎉

## Disclaimer

This plugin is provided as-is and is designed for personal use. It has not
been tested on every platform and may not work as expected with all future updates.
If you notice something is not working as intended, please open a bug report or
pull request so it can be fixed.

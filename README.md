# Beacher's Shitty MMO — Alpha Client

A WoW-inspired indie MMORPG built in Godot 4. This repo hosts the **game client downloads and update feed** for closed alpha testers — the game source lives elsewhere.

---

## 🚀 Install (one file, one double-click)

1. **Make a folder** for the game, e.g. `C:\Games\BeachersShittyMMO`.
2. **Download [`install.bat`](https://github.com/TomSomerville/BeachersShittyMMO-releases/releases/latest/download/install.bat)** into that folder.
3. **Double-click it.** It downloads the client (~1 GB), creates a **Beachers Shitty MMO** shortcut in the folder and on your Desktop, and starts the launcher.

> ⚠️ **Always start the game from the shortcut — never the `.exe` directly.**
> The shortcut runs the launcher, which keeps your install up to date automatically.

## 🎮 First launch

1. If Windows SmartScreen appears: **More info → Run anyway** (the build is unsigned — normal for an alpha).
2. In the launcher, **register** a username and password.
3. **Log in**, create a character, and play.

## 🔄 Updates

Nothing to do — every time you open the launcher it checks for a new version and downloads **only the files that changed** (usually a small ~33 MB patch, not the full client).

## 🛠 Troubleshooting

| Problem | Fix |
|---|---|
| Download died mid-install | Run `install.bat` again — finished files are kept, broken ones re-download. |
| Game looks broken after a patch | Open the launcher again — it re-verifies every file against the update manifest. |
| Can't connect / stuck at login | The server is probably down — ping the dev. |

## 📦 Manual download

Prefer to grab files yourself? Everything is on the [latest release](https://github.com/TomSomerville/BeachersShittyMMO-releases/releases/latest) — you need the `.exe`, all four `.pck` files, and both `.dll` files in one folder, then run the exe with `--launcher`.

---

*Closed alpha — expect breaking changes, character wipes, and rough edges. That's the fun part.*

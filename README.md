## GameMaker 8.1 – Local Installer Repo

This repository provides a **local copy of the GameMaker 8.1 installer** for personal archival and experimentation with legacy **GML** projects.

---

### Repo Layout

- **`Installer/GameMaker-Installer-8.1.exe`**: The GameMaker 8.1 installer executable.

There are currently **no project files** (`.gmk` / `.gm81`) checked into this repo.

---

### System Requirements (Typical)

- **Operating System**: Windows 7 (32‑bit or 64‑bit) or later  
  - Commonly used on: Windows 7, Windows 10, Windows 11  
- **CPU**: Any x86-compatible CPU from the Windows 7 era or newer  
- **RAM**: 1 GB minimum (2 GB+ recommended)  
- **Disk Space**: ~200 MB for GameMaker 8.1 itself, plus extra for your projects/assets

Actual behavior can vary on very new Windows builds; see the compatibility notes below if you hit issues.

---

### Installing GameMaker 8.1 (Using This Repo)

1. **Locate the installer**  
   - Navigate to this repo’s root in Explorer.  
   - Open the `Installer` folder.  
   - Confirm you see `GameMaker-Installer-8.1.exe`.

2. **Run the installer**  
   - Right-click `GameMaker-Installer-8.1.exe`.  
   - Choose **“Run as administrator”** (recommended on modern Windows).  
   - Follow the setup wizard, accept the license, and keep the default install path unless you have a strong reason to change it.

3. **(If needed) Enable compatibility mode**  
   If you see crashes, graphic glitches, or odd behavior:
   - Right-click the installed `Game_Maker.exe` (or its shortcut).  
   - Go to **Properties → Compatibility**.  
   - Check **“Run this program in compatibility mode for”** and pick **Windows 7**.  
   - Optionally check **“Run this program as an administrator”** as well.

---

### Licensing / Activation

GameMaker 8.1 is **end-of-life** and **no longer sold** by the publisher.

- If you **already own a valid legacy license**, you can enter your key inside GameMaker 8.1’s registration dialog.  
- If you **do not own a license**, you are limited to whatever **trial / free mode** this installer provides and should **not** attempt to bypass licensing.  
- For any serious or commercial work, you should strongly prefer the **current, supported version of GameMaker** instead.

This repo is intended for **historical and educational use only**, not for circumventing licensing.

---

### Running GameMaker 8.1

After installation:

1. Launch **GameMaker 8.1** from the Start Menu or desktop shortcut.  
2. When prompted, either:
   - Enter your **existing license key**, or  
   - Continue with the **trial / free** mode (if available).  
3. You should see the classic IDE with:
   - Resource tree (sprites, sounds, objects, rooms, etc.)  
   - GML code editor  
   - Room editor and other built‑in tools

---

### Using It With Projects

This repo does **not** contain example projects, but once GameMaker 8.1 is installed you can:

- **Open existing projects**:  
  - Start GameMaker 8.1 → **File → Open** → select `.gmk` or `.gm81` files from your own folders.  
- **Create new projects**:  
  - **File → New**, add sprites/sounds/objects/rooms, write GML code, and run the game from the toolbar.

Be aware that many older projects rely on **32‑bit DLLs** or outdated extensions, which may misbehave on modern systems.

---

### Notes & Limitations

- **Unsupported**: GameMaker 8.1 no longer receives updates or official support.  
- **Compatibility**: It usually works on modern Windows but may break with future OS updates or security changes.  
- **Missing modern features**: No modern shader pipeline, no current‑gen workflow UI, fewer quality‑of‑life tools.  
- **Not recommended for new commercial games**: Use the latest GameMaker for anything long‑term or revenue‑generating.

---

### Project Purpose

- **Goal**: Keep a **local, self-contained installer** for GameMaker 8.1 to make it easy to spin up a legacy environment.  
- **Intended use**:
  - Open and run old GM8/8.1 games you already have.  
  - Study historical GML patterns and workflows.  
  - Perform small experiments or archival work, not modern production development.



## GameMaker 8.1 – Setup & Usage Guide

This project is meant to explore games that were made in the past using the **GML** language with **GameMaker 8.1**.  
The instructions below explain how to get GameMaker 8.1 running on a modern Windows machine.

---

### System Requirements

- **Operating System**: Windows 7 (32-bit) or above  
  - Tested on:  
    - Windows 7 (32-bit / 64-bit)  
    - Windows 10 / 11 (via compatibility mode, if needed)
- **CPU**: Any x86-compatible processor from the Windows 7 era or newer  
- **RAM**: 1 GB minimum (2 GB+ recommended)
- **Disk Space**: ~200 MB free for GameMaker 8.1, plus additional space for project files and assets

---

### 1. Getting the GameMaker 8.1 Installer

GameMaker 8.1 is **deprecated** and no longer officially sold, but the installer can still sometimes be found via:

- **Official legacy download locations** (YoYo Games / Opera legacy pages, if still available)
- **Reputable archival sources** that mirror older versions of GameMaker

When downloading:

- **Only use trusted sources**
- **Verify file integrity** where possible (checksums, community verification, etc.)
- Avoid any installers bundled with extra “toolbars”, “optimizers”, or other adware

> Note: GameMaker 8.1 is obsolete and unsupported. For new, commercial, or long-term projects, consider the current version of GameMaker instead.

---

### 2. Installing GameMaker 8.1

1. **Run the installer**  
   - Right-click the installer (`GM81.exe` or similar)  
   - Choose **“Run as administrator”** (recommended on newer Windows versions)

2. **Follow the setup wizard**  
   - Accept the license terms  
   - Choose an install directory (the default is usually fine)  
   - Complete the installation

3. **(Optional) Set compatibility mode on newer Windows versions**  
   If you encounter crashes or UI glitches:
   - Right-click the `Game_Maker.exe` shortcut or executable  
   - Select **Properties → Compatibility**  
   - Enable **“Run this program in compatibility mode for”** and choose **Windows 7**  
   - Also consider checking **“Run this program as an administrator”**

---

### 3. Licensing / Activation

GameMaker 8.1 is no longer sold. That means:

- **You cannot buy new licenses** from the official publisher
- If you **already own a valid GameMaker 8 / 8.1 license**, you can:
  - Enter your existing license key in the **License / Registration** dialog within GameMaker 8.1
- If you **do not own a legacy license**, you should:
  - Use GameMaker 8.1 only within whatever **trial / free limitations** the installer provides, or  
  - Prefer the **current, supported version of GameMaker** for serious or commercial projects

This project is focused on **historical exploration and learning**, not on bypassing license checks.

---

### 4. Running GameMaker 8.1

After installation:

1. Launch **GameMaker 8.1** from the Start Menu or desktop shortcut.
2. If prompted:
   - Enter your existing license (if you have one), or  
   - Continue with any available free / trial mode.
3. You should now see the classic GameMaker 8.1 IDE with:
   - Resource tree (sprites, sounds, objects, rooms, etc.)
   - Code editor for **GML**
   - Room editor and other classic tools

---

### 5. Opening Existing Projects

This repository is intended to explore old GML-based projects.

To open them:

1. Start GameMaker 8.1.
2. Go to **File → Open**.
3. Select a project file:
   - `.gmk` (GameMaker 7 / 8 format)  
   - `.gm81` (GameMaker 8.1 format), if available
4. Verify that:
   - Sprites, sounds, objects, and rooms load correctly  
   - Any external DLLs or resources are present in the project folders

> Some old projects may rely on **32-bit DLLs** or outdated extensions. These may not work correctly on modern systems or without additional configuration.

---

### 6. Creating / Editing Projects

Within GameMaker 8.1 you can:

- **Create new projects** via **File → New**
- **Add resources** using the right-click context menus in the resource tree:
  - Sprites, Sounds, Backgrounds, Objects, Rooms
- **Write GML code** by:
  - Double-clicking an object → adding events → switching to the **Code** actions
- **Run your game** with the **Run** / **Play** button in the toolbar

This is ideal for:

- Exploring how old GML codebases were structured  
- Learning historical patterns and limitations of older GameMaker workflows  
- Running and studying legacy games made with GM8/8.1

---

### 7. Notes & Limitations

- **No official support**: GameMaker 8.1 is unsupported by its original developer.
- **Limited OS compatibility**:  
  While it generally runs on modern Windows, future OS updates may break it.
- **No modern features**:
  - No built-in shader pipeline like recent GameMaker versions
  - Older room editor, no modern workspace UI, and many quality-of-life features are missing
- **Not recommended for new commercial projects**:
  - For serious, long-term development, use the current version of GameMaker instead.

---

### 8. Project Purpose

- **Goal**: Explore and understand **legacy GameMaker (GM8.1) games** and the **GML** language as it was used in the past.
- **Scope**:
  - Open and run old GM8/8.1 projects
  - Study old GML scripts, object behavior, and design patterns
  - Optionally make minor modifications to better understand how these games were built

If you want, I can next:

- Add example sections for **common troubleshooting** (crashes, missing DLLs, etc.), or  
- Document how to **migrate** an old GM8.1 project toward newer versions of GameMaker.



```markdown
## References

- [Possible to buy a GameMaker 8.1 license? – r/gamemaker](https://www.reddit.com/r/gamemaker/comments/1hnpq4k/possible_to_buy_a_gamemaker_81_license/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
```


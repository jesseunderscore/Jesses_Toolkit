# *Jesse's Toolkit*

My desktop suite built for developers (specifically Roblox).

![Hero Image](https://i.ibb.co/JRd4qqrF/Hero-JToolkit.png)

---

## Features

| Tool | Description |
|------|-------------|
| **Alpha Fixer** | Fixes transparent PNG fringing and colour bleeding on edges |
| **Game Planner** | Visual node-based canvas for planning your games |
| **Notes** | Persistent tabbed notes for dev thoughts, scripts, and references |
| **Image Compressor** | Batch compress images without leaving the app |
| **Gamepass Maker** | Build and organise your Roblox gamepass layouts |
| **Texture Tiler** | Load any image and tile it into a repeating grid with rotation and spacing controls |
| **Appearance** | multiple themes: Void, Ocean, Emerald, Crimson, Amber, Camila, Jesse |

---

## Setup

No installation required.

1. Download the latest release zip
2. Extract the folder anywhere on your PC
3. Run `JessesToolkit.exe`

Dependencies are in the lib folder, nothing to install though.

---

## Data & Save Files

All data is stored locally in a `JTdata/` folder, created automatically next to the `.exe` on first launch.

```
JessesToolkit/
├── JessesToolkit.exe
├── JesseToolkitIcon.ico
└── JTdata/
    ├── notes.json
    ├── settings.json
    ├── appearance.json
    ├── planners/
    └── gamepasses/
```

To wipe your data manually, delete the `JTdata/` folder. The app will regenerate it fresh on next launch.

---

## Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Z` | Undo (Game Planner) |
| `Ctrl + Y` | Redo (Game Planner) |
| `Ctrl + V` | Paste image or text as node |
| `Double-click` | New node on canvas |
| `Right-drag` | Pan the canvas |
| `Scroll` | Zoom in / out |
| `Del` | Delete selected node |

---

Made by **@jessexlr**.

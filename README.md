<p align="center">
  <img src="assets/logo-wide.png" alt="GerbDiff" width="500">
</p>

<h3 align="center">Visual diff tool for Gerber PCB files</h3>

<p align="center">
  Compare two revisions of a PCB design side-by-side, overlaid, or with XOR diff highlighting.<br>
  Instantly spot copper changes, silkscreen edits, drill modifications, and more.
</p>

<p align="center">
  <a href="https://github.com/woodruffrb/gerbdiff-releases/releases/latest"><strong>Download Latest Release</strong></a>
</p>

---

## Features

- **Side-by-side & overlay views** — compare two Gerber projects with color-coded layers
- **Automatic layer matching** — detects and pairs layers across project revisions
- **Change region detection** — highlights areas that differ between revisions
- **Region navigation** — step through changes one by one with N/P keys
- **Measurement tool** — measure distances directly on the board
- **Multi-layer support** — copper, soldermask, silkscreen, solderpaste, drill, board outline
- **Full Gerber support** — X1, X2, aperture macros, step-and-repeat, Excellon drill
- **Export reports** — generate PNG or HTML summary reports
- **Auto-alignment** — automatically registers boards even if origins differ

## Getting Started

1. **Download** the latest installer from the [Releases](https://github.com/woodruffrb/gerbdiff-releases/releases/latest) page
2. **Run** the installer (`GerbDiff Setup 1.0.0.exe`) — Windows x64
3. **Import** two Gerber project folders (drag & drop or File > Import)
4. **Compare** — switch between Side-by-Side and Overlay views, navigate changes

> **Note:** The installer is not code-signed yet, so Windows SmartScreen may show a warning. Click "More info" > "Run anyway" to proceed.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Ctrl+O` | Import Project A |
| `Ctrl+Shift+O` | Import Project B |
| `N` / `P` | Next / Previous change region |
| `M` | Toggle measurement mode |
| `Ctrl+G` | Toggle gridlines |
| `Ctrl+Shift+E` | Export summary report |
| `Scroll wheel` | Zoom in/out |
| `Click + drag` | Pan view |

## Feedback

This is an early release and we'd love your feedback! Please open an [Issue](https://github.com/woodruffrb/gerbdiff-releases/issues) for:

- Bug reports
- Feature requests
- General feedback on the workflow

## System Requirements

- Windows 10/11 (x64)
- ~200 MB disk space

## License

Copyright (c) 2026 Ben Woodruff. All rights reserved.

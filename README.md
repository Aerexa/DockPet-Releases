# DockPet Releases

Official download and update feed for **DockPet** — a native macOS menu bar companion with a pixel-art pet along the bottom of your screen.

This repository hosts release builds only. Application source code is maintained separately.

## Download

Go to **[Releases](https://github.com/Aerexa/DockPet-Releases/releases)** and download the latest `.dmg`.

| Requirement | Details |
|-------------|---------|
| macOS | 15.6 or later |
| Architecture | Apple Silicon & Intel |

### Install

1. Open the downloaded `.dmg`
2. Drag **DockPet** to **Applications**
3. Launch DockPet — look for the paw icon in the menu bar

**First launch blocked?** Right-click DockPet in Applications → **Open**, then confirm. This can happen before the app is notarized with Apple.

## What’s included

- Pixel-art pet with day/night behavior and persistent stats
- Menu bar controls: Settings, Stay Awake, Feed, Check for Updates
- Optional clipboard history with a global hotkey

## Updates

DockPet checks for updates automatically (Sparkle). You can also use **Check for Updates…** from the menu bar.

The update feed is served from [`appcast.xml`](appcast.xml) on this repo’s `main` branch.

## Repository layout

```
DockPet-Releases/
├── README.md       ← this file
├── appcast.xml     ← Sparkle update feed (on main)
└── releases/       ← optional; binaries are attached to GitHub Releases
```

DMG files are attached to each [GitHub Release](https://github.com/Aerexa/DockPet-Releases/releases), not committed to git.

## Feedback

Open an issue on this repository or contact the maintainer.

## License

DockPet is © Aerexa. All rights reserved unless otherwise stated.

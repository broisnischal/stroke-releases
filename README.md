# Stroke

Fast desktop database client for PostgreSQL, MySQL, SQLite, and Cloudflare D1.

This repository hosts **releases and install manifests**. The source code is developed in a private repository.

## Install

**macOS** — [Homebrew](https://brew.sh)

```bash
brew install --cask broisnischal/tap/stroke
```

**Windows** — [Scoop](https://scoop.sh)

```powershell
scoop bucket add stroke https://github.com/broisnischal/stroke
scoop install stroke
```

**Or download directly** from the [Releases](https://github.com/broisnischal/stroke/releases) page:

| Platform | File |
|----------|------|
| macOS (Apple Silicon) | `stroke_x.x.x_aarch64.dmg` |
| macOS (Intel) | `stroke_x.x.x_x64.dmg` |
| Windows | `stroke_x.x.x_x64-setup.exe` |
| Linux (Debian/Ubuntu) | `stroke_x.x.x_amd64.deb` |
| Linux (AppImage) | `stroke_x.x.x_amd64.AppImage` |

**macOS** — if the app is blocked on first launch: `xattr -cr /Applications/Stroke.app`
**Windows** — on SmartScreen, click **More info → Run anyway** (Scoop installs skip this).

Stroke updates itself automatically once installed.

## Issues

Found a bug or have a feature request? [Open an issue](https://github.com/broisnischal/stroke/issues).

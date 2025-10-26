<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">Shy Launcher</h1>

[<p align="center"><img src="https://img.shields.io/github/actions/workflow/status/CraftingGamesNet/ShyLauncher/build.yml?branch=master&style=for-the-badge" alt="gh actions">](https://github.com/CraftingGamesNet/ShyLauncher/actions) [<img src="https://img.shields.io/github/downloads/CraftingGamesNet/ShyLauncher/total.svg?style=for-the-badge" alt="downloads">](https://github.com/CraftingGamesNet/ShyLauncher/releases)

<p align="center">Join Faywyn without worrying about installing Fabric. We'll handle that for you.</p>
<p align="center">(The launcher is not necessary to play on the server, but it makes it easier with cool features.)</p>

## Downloads

You can download from [GitHub Releases](https://github.com/CraftingGamesNet/ShyLauncher/releases)

#### Latest Release

[![](https://img.shields.io/github/release/CraftingGamesNet/ShyLauncher.svg?style=flat-square)](https://github.com/dscalzi/ShyLauncher/releases/latest)

#### Latest Pre-Release
[![](https://img.shields.io/github/release/CraftingGamesNet/ShyLauncher/all.svg?style=flat-square)](https://github.com/dscalzi/ShyLauncher/releases)

**Supported Platforms**

If you download from the [Releases](https://github.com/CraftingGamesNet/ShyLauncher/releases) tab, select the installer for your system.

| Platform | File | Status |
| -------- | ---- | ------ |
| Windows x64 | `Shy-Launcher-setup-VERSION.exe` | (available) |
| macOS x64 | `Shy-Launcher-setup-VERSION-x64.dmg` | (not available) |
| macOS arm64 | `Shy-Launcher-setup-VERSION-arm64.dmg` | (not available) |
| Linux x64 | `Shy-Launcher-setup-VERSION.AppImage` | (not available) |

## Development

This section details the setup of a basic developmentment environment.

### Getting Started

**System Requirements**

* [Node.js][nodejs] v20

---

**Clone and Install Dependencies**

```console
> git clone https://github.com/CraftingGamesNet/ShyLauncher.git
> cd ShyLauncher
> npm install
```

---

**Launch Application**

```console
> npm start
```

---

**Build Installers**

To build for your current platform.

```console
> npm run dist
```

Build for a specific platform.

| Platform    | Command              |
| ----------- | -------------------- |
| Windows x64 | `npm run dist:win`   |
| macOS       | `npm run dist:mac`   |
| Linux x64   | `npm run dist:linux` |

Builds for macOS may not work on Windows/Linux and vice-versa.

---

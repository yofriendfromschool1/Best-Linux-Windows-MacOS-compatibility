# 🐧 Best Linux · Windows · macOS Compatibility

> A curated list of the best tools, compatibility layers, and virtual machines for running
> **Windows apps on Linux**, **Windows/Linux apps on macOS**, and **Linux/macOS apps on Windows**.

Whether you're a gamer, a developer, or just someone who needs *that one* Windows program,
there's a good chance one of the tools below will do the job.

---

## 📑 Table of Contents

- [Windows Apps on Linux](#-windows-apps-on-linux)
  - [Wine & Compatibility Layers](#wine--compatibility-layers)
  - [Launchers & Managers](#launchers--managers)
  - [Commercial Solutions](#commercial-solutions)
  - [Virtual Machines](#virtual-machines)
  - [Dual Boot](#dual-boot)
- [macOS Apps on Linux](#-macos-apps-on-linux)
- [Windows Apps on macOS](#-windows-apps-on-macos)
- [Linux Apps on macOS](#-linux-apps-on-macos)
- [Linux & macOS Apps on Windows](#-linux--macos-apps-on-windows)
- [Quick Recommendations](#-quick-recommendations)
- [Legal & Ethical Note](#-legal--ethical-note)
- [Contributing](#-contributing)

---

## 🪟 Windows Apps on Linux

### Wine & Compatibility Layers

| Tool | Description | Link |
|------|-------------|------|
| **Wine** | The foundation of nearly everything here — a compatibility layer that runs Windows apps natively on Linux. | [Download](https://gitlab.winehq.org/wine/wine/-/wikis/Download) |
| **Winetricks** | Helper script that installs missing DLLs, fonts, and runtime components Wine apps often need. | [GitHub](https://github.com/Winetricks/winetricks) |
| **Proton** | Valve's Wine fork with extra patches, used by Steam to run Windows games on Linux. | [GitHub](https://github.com/ValveSoftware/Proton) |
| **ProtonTricks** | Winetricks for Proton prefixes — tweak individual Steam games. | [Flathub](https://flathub.org/en/apps/com.github.Matoking.protontricks) · [GitHub](https://github.com/Matoking/protontricks) |

### Launchers & Managers

| Tool | Description | Link |
|------|-------------|------|
| **Bottles** | Friendly GTK app for managing Wine prefixes ("bottles"), with per-app tweaks and Flatpak support. | [usebottles.com](https://usebottles.com/) |
| **Lutris** | All-in-one game launcher that manages Wine, Proton, and emulators from a single interface. | [lutris.net](https://lutris.net/) |
| **Heroic Games Launcher** | Open-source launcher for Epic Games, GOG, and Amazon Games on Linux. | [GitHub](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher) |
| **WinBoat** | Run Windows apps in a containerised Windows VM and integrate them into your Linux desktop. | [winboat.app](https://www.winboat.app/) |
| **WinApps** | Seamlessly run Windows apps (including Microsoft Office and Adobe) in a KVM/VMware/Docker VM, appearing as native Linux windows. | [GitHub (original)](https://github.com/Fmstrat/winapps) · [GitHub (org)](https://github.com/winapps-org/winapps) |

### Commercial Solutions

| Tool | Description | Link |
|------|-------------|------|
| **CrossOver** | CodeWeavers' polished, commercially supported Wine. Excellent app compatibility and official support (paid, free trial available, but pirating is also a choice 1337x, etc.). | [codeweavers.com](https://www.codeweavers.com/crossover/) |

### Virtual Machines

- **VirtualBox** — Free, cross-platform, easiest to set up.
- **KVM / QEMU** — Near-native performance on Linux; pair with **virt-manager** or **GNOME Boxes** for a GUI.
- **VMware Workstation** — Free for personal use, great 3D acceleration.
- **GNOME Boxes** — Simple, user-friendly frontend for KVM.

> 💡 **Tip:** VMs are the most reliable route for demanding Windows software, but expect limited GPU performance unless you set up GPU passthrough.

### Dual Boot

The most compatible option of all — full native performance, but you must reboot to switch OSes.
Consider it if you need Windows for work, gaming, or hardware-specific software.

---

## 🍎 macOS Apps on Linux

| Tool | Description | Link |
|------|-------------|------|
| **Darling** | A macOS translation layer for Linux — lets you run macOS CLI tools and some binaries. | [darlinghq.org](https://www.darlinghq.org/) |

> ⚠️ Darling is still experimental and best suited for command-line macOS software, not full GUI apps.

---

## 🪟 Windows Apps on macOS

| Tool | Description | Link |
|------|-------------|------|
| **CrossOver** | Commercial Wine-based solution with strong app compatibility and official support (paid, free trial, 1337x). | [codeweavers.com](https://www.codeweavers.com/crossover/) |
| **Whisky** | Modern, user-friendly Wine wrapper for macOS built on Wine and Apple's Game Porting Toolkit (free, open source). | [getwhisky.app](https://getwhisky.app/) · [GitHub mirror](https://github.com/ybmeng/moonshine) |
| **PlayOnMac (POM)** | Wine-based launcher for Windows games and apps, similar to PlayOnLinux. | [playonmac.com](https://www.playonmac.com/) |
| **Pixel Port** | Play windows games steams on mac | [pixelport.gg](https://pixelport.gg/) |
| **Highball** | Lightweight Wine frontend for Apple Silicon Macs. | [gethighball.com](https://gethighball.com/) |
| **Parallels Desktop** | The most seamless macOS VM solution — runs Windows 11 (including ARM builds) with near-native performance (paid). | [parallels.com](https://www.parallels.com/products/desktop/) |
| **UTM** | Free, open-source QEMU-based VM manager for macOS — great for Windows/Linux VMs on Apple Silicon. | [mac.getutm.app](https://mac.getutm.app/) |

> 💡 **Apple Silicon tip:** Apple's **Game Porting Toolkit (GPTK)**, included with the Command Line Tools, provides a D3DMetal translation layer that dramatically improves Windows gaming performance under Wine.

---

## 🐧 Linux Apps on macOS

| Tool | Description | Link |
|------|-------------|------|
| **ELFuse** | Runs Linux ELF binaries on macOS via a syscall-translation layer. | [GitHub](https://github.com/sysprog21/elfuse) |
| **Docker / Podman** | Run Linux containers natively on macOS — the most practical way to use Linux software. | [docker.com](https://www.docker.com/) |
| **UTM** | Full Linux VMs on Apple Silicon, with excellent performance. | [mac.getutm.app](https://mac.getutm.app/) |

---

## 🪟 Linux & macOS Apps on Windows

| Tool | Description | Link |
|------|-------------|------|
| **WSL 2** | Microsoft's official Linux subsystem — run real Linux distros (GUI included) directly on Windows. | [Install guide (Microsoft)](https://learn.microsoft.com/en-us/windows/wsl/install) · [Setup gist](https://gist.github.com/djibe/c60f6a055779ad89b5f84f81a2d337f7) |
| **Cygwin** | Long-standing POSIX compatibility layer providing Linux-like tools on Windows. | [cygwin.com](https://www.cygwin.com/) |
| **MSYS2** | Modern POSIX environment with the `pacman` package manager — the go-to for building native Windows software with Unix tooling. | [msys2.org](https://www.msys2.org/) |
| **Darling** | Run macOS CLI applications on Windows via WSL 2. | [WSL build guide](https://docs.darlinghq.org/wsl-build.html) |

---

## ⚡ Quick Recommendations

| Your situation | Start with |
|----------------|------------|
| Just want to run one Windows `.exe` on Linux | **Bottles** (or **Lutris** for games) |
| Windows games on Linux | **Steam + Proton**, then **Heroic** / **Lutris** |
| Microsoft Office / Adobe on Linux | **WinApps** or a **Windows VM** |
| Windows apps on Apple Silicon Mac | **Whisky** (free) or **CrossOver** / **Parallels** (paid) |
| Linux tooling on Windows | **WSL 2** |
| Building Windows software with Unix tools | **MSYS2** |
| Maximum compatibility, no compromises | **Dual boot** |

---

## ⚖️ Legal & Ethical Note

- **CrossOver** and **Parallels Desktop** are commercial products. Please purchase a license or use their official free trials — both companies support ongoing development of this ecosystem.
- Windows itself requires a valid license when run in a VM.
- Only use software and ROMs you legally own. Piracy is not endorsed by this list.

---

## 🤝 Contributing

Found a great tool that's missing? Contributions are welcome!

1. Fork the repo.
2. Add your tool in the correct section, keeping alphabetical order where possible.
3. Include a **short description** and an **official link**.
4. Open a pull request.

Please only submit tools that are actively maintained or historically significant.

---

## 🔗 Related Awesome Lists

- [Awesome Linux Software](https://github.com/luong-komorebi/Awesome-Linux-Software)
- [Awesome Wine](https://github.com/Kreyren/awesome-wine)
- [Awesome macOS](https://github.com/jaywcjlove/awesome-mac)
- [Awesome Windows](https://github.com/0PandaDEV/awesome-windows)

---

<div align="center">

**⭐ If this list helped you, consider giving it a star!**

</div>

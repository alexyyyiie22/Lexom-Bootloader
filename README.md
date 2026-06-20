# Lexom Bootloader V0.1
### Monolithic x86_64 Bare-Metal UEFI Boot Management System
---

Lexom is an independent, bare-metal x86_64 UEFI bootloader engineered entirely from scratch in C. Built to interface directly with Unified Extensible Firmware Interface (UEFI) specifications via the lightweight `posix-uefi` hardware layer, Lexom completely eliminates the need for legacy BIOS sector-hacking, 16-bit real-mode transitions, or heavy pre-built boot manager configurations.

Unlike standard boot managers that rely on static, hardcoded textual configuration files (`.cfg` or `.json`) which can lie about what is on the drive, Lexom implements a strict **hardware-probing architecture**. Upon system initialization, it mounts available storage handles via the motherboard's native file system protocols, executing deep path-verification routines to dynamically map real, bootable operating system payloads physically present on the disk architecture.

---

## 🖥️ Operational User Interface Layout

Lexom targets a clean, high-scannability system layout using standard firmware character grids. Below is the exact UI configuration rendered by the layout execution engine:

Lexom Bootloader V0.1
--------------------------------------------------------------------------------------------------
Available Boot Options:
  Windows 11 •
  GempOS
--------------------------------------------------------------------------------------------------
• Is The Current One Selected To Boot.
To Boot A OS Select One And Click Enter.
To Navagate The OS Menu Just Use The Up And Down Arrows On Your Keyboard.
To Raname One SelectOne And Click R.
To Add One Click A And Select From Avalible Devices.
To Delete One Select It And Type D.
To Exit The Bootloader Type E.
2026.
bash'''
LEXOM BOOTLOADER IS NOT FOR DAILY DRIVER USE AND IS NOT GOOD.

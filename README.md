<div align="center">

# RL-File-Switcher

*Swap Rocket League cosmetic files instantly — per account, per profile.*

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download](https://img.shields.io/badge/Download-RLFileSwitcher_1.1.2-0d6efd?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Bxnny24/RL-File-Switcher-releases/releases/latest/download/RLFileSwitcher-win-Setup.exe)

![Platform](https://img.shields.io/badge/platform-Windows_10%2F11-lightgrey?style=flat-square&logo=windows)
![Version](https://img.shields.io/badge/version-1.1.2-0d6efd?style=flat-square)
<!-- END LATEST DOWNLOAD BUTTON -->

</div>

---

## What is RL-File-Switcher?

RL-File-Switcher is a lightweight Windows tray app for Rocket League players who want to switch between different cosmetic setups quickly — supports **Steam**, **Epic Games**, and both simultaneously.

Instead of manually replacing files each time, RL-File-Switcher lets you:

- **Swap cosmetic files** (decals, wheels, toppers, boost effects, and more) with a single click
- **Create profiles** to save and restore full cosmetic loadouts
- **Bind profiles to accounts** — switching accounts automatically loads the right profile
- **Run silently in the system tray** — launches with Windows, stays out of your way
- **Get toast notifications** when profiles are switched automatically

No game files are modified permanently. Originals are always preserved and can be restored instantly.

---

## Is this safe? (EAC)

RL-File-Switcher **only ever modifies `.upk` files** — the cosmetic asset packages used by Rocket League. No executables, no configuration files, nothing else is touched.

Easy Anti-Cheat (EAC) targets runtime manipulation: memory injection, DLL hooking, and process tampering. It does not monitor cosmetic asset files on disk.

Additionally, the app **blocks all file swaps while Rocket League is running**, so files are only changed when EAC is fully inactive. Originals are always backed up and can be restored in one click.

> Cosmetic UPK swapping has been practised by the Rocket League community for years without reported EAC issues. However, modding always carries some inherent risk — use at your own discretion.

---

> This repository is the **official release channel** for RL-File-Switcher.
> All releases here are used by the app for automatic updates.

![Tech Company Presentation](https://github.com/SenseiiX/SenseiiX/blob/main/fusionx.png?raw=true)

# FusionX Kernel for POCO F4 (munch)
> ✅ **Supports MIUI / HyperOS / AOSP / LOS / CLO**

Custom & optimized kernel for POCO F4 / Redmi K40S based on latest Linux, Google, and CodeLinaro tags. Built with AOSP Clang + FULL LTO + Polly, -O3, and MLGO, targeting stability, efficiency, and **customizability**.

## 🔍 Highlights

- **Modern Base:** Based on **N0Kernel**, updated to latest **Linux 4.19.xx**, **Google ASB**, and **CodeLinaro** tags
- **Fully Optimized:** Compiled with **Clang + LTO + Polly**, aggressive `-O3` optimizations, and **MLGO**
- **Stability First:** Prioritizes stability for daily use and gaming
- **Highly Customizable:** Scheduler performance tuning, bypass charging, more root manager support

## 🚀 Key Features
- **Wide range of KSU based manager support**: 
    - OG KSU, SukiSU Ultra, KSU-Next, MkSU, RkSU, backlashxx's fork
- **SUSFS Integration**: Enhanced root hiding capability
- **Display Enhancements**: Includes **DC Dimming** and **High Brightness Mode (HBM)**
- **Sched Boost Tunableses**: Customizable performance curve
- **Hiding Capabilities**: Better zygisk hiding and faked all lineage symlinks
- **Bypass Charging**: Extend battery life during gaming or long usage
- **Smart Installer**: Dual-mode installer supporting:
  - Auto-detects ROM/CPU type via zipname (for adb sideload, recoveries or kernel flashers)
  - Manual selection with volume keys (for adb sideload, recoveries or kernel flashers)

---

## 📦 Available Variants

**NEXT**
- Modern root solution
- Light, clean, and simple
- Focus on stability and performance

**NEXT + SUSFS**
- Adds SUSFS root hiding system
- Ideal for apps/games with root detection (banking, anti-cheat)
- Heavier, but more secure

---

## 💡 Installation Methods

### Requirements

- Unlocked bootloader
- Custom Recovery (TWRP/OrangeFox) or adb sideload
- Supported ROM (AOSP, MIUI/HyperOS, LOS, CLO/CAF)
- Backup of stock kernel

### Method 1: Auto-detection via File Naming

- The installer will detect your ROM automatically based on the filename:

| ROM Type           | Filename Example                |
|--------------------|----------------------------------|
| MIUI / HyperOS     | FusionX-vX.X-`MIUI`.zip         |
| AOSP w/ LOS IR     | FusionX-vX.X-`IR`.zip           |
| AOSP (standard)    | FusionX-vX.X-`AOSP`.zip              |


- The installer also detects your CPU frequency of the prime core:

| CPU Type         | Detection Method                     | Example Filename                |
|------------------|--------------------------------------|----------------------------------|
| MAX   | Prime core freq = `3.2 GHz`         | FusionX-vX.X-ROM-.zip (blank)      |
| BALANCE   | Prime core freq = `2.8 GHz`         | FusionX-vX.X-ROM-`BAL`.zip       |
| EFFICIENT   | Prime core freq = `2.5 GHz`         | FusionX-vX.X-ROM-`EFF`.zip       |

Just flash normally in your custom recovery.

### Method 2: Manual Selection (ADB Sideload or Custom Recoveries)

1. Boot into recovery and flash the kernel zip
2. volume keys to choose your ROM/CPU freq type:
3. Confirm your choice when prompted

---

### ⚠️ Disclaimer

**I AM NOT RESPONSIBLE IF YOUR DEVICE GETS BRICKED!**

You flash this kernel at your own risk. Make sure to create a stock kernel backup before installation.

---

## 🤝 Credits

- **@EmanuelCN**: N0Kernel development
- **@simonpunk & @sidex15**: SUSFS
- **@osm0sis**: AnyKernel3 framework
- **@viasco**: For this read.me template
- **Kernel developers**: Cherry-picked commits
- **Google**: Clang compiler
- **KSU manager developers**: OG KSU, SukiSU Ultra, KSU-Next, MkSU, RkSU, backlashxx's fork
- **All testers and contributors**: For their valuable feedback and support

---

## 📞 **Support**

If you have any questions, issues, or suggestions, feel free to reach out:

- **Telegram Channel**: [Open Channel](https://t.me/fusi0nx)  
- **Telegram Group**: [Open Group](https://t.me/senseixhub)  

---

## 📄 License

This project uses GPL v2 license in accordance with the Linux kernel.

---

**If this kernel is useful for you, don't forget to give a ⭐ star to this [repository!](https://github.com/SenseiiX/fusionX_sm8250)**

# kyotogodchi

Kyoto’s personal configuration for **Pwnagotchi**.

<img width="2560" height="1252" alt="github" src="https://github.com/user-attachments/assets/9cc74b5c-25f4-43cb-8fb7-77fe53a8aa73" />

---

## Overview

**kyotogodchi** is a customized Pwnagotchi configuration optimized for Waveshare v3/v4 displays and Chinese UPS modules.  
It focuses on visual clarity, compatibility, and a clean user experience while keeping useful plugin functionality like displaying cracked Wi-Fi passwords and battery status.

---

## Plugins

### 🧩 display-password-kyoto
A [CrackHouse](https://github.com/V0r-T3x/pwnagotchi_LCD_colorized_darkmode/blob/b5792224f1c17b6f14e2acac1e28470cdd424983/files/crack_house.py)-inspired plugin adapted for **Waveshare v3** and **v4** displays.

- Works together with **wpa-sec**.
- Displays the **nearest hacked Wi-Fi** and its password (if in range).
- If the access point is out of range, shows the **last hacked AP** instead.

---

### 🔋 [ups_plugin_1_3](https://github.com/PhreakBoutique/UPSLite_Plugin_1_3/blob/main/upslite_plugin_1_3.py)
A slightly modified version of the original UPSLite plugin.

- Removed charging status (+/–) indicator since most Chinese UPS boards don’t support it.
- Added a **percent (%)** sign for a cleaner battery level display.

---

### 💾 [memtemp-plus](https://github.com/crahan/pwnagotchi-plugins/blob/main/memtemp-plus.py) && 🧠 [exp](https://github.com/GaelicThunder/Experience-Plugin-Pwnagotchi/blob/master/exp.py)

- Both plugins have **adjusted display coordinates** for better alignment on Waveshare screens.  
- Text labels slightly changed (e.g., **Exp → XP**) for a cleaner and more compact look.

---

### ⚙️ Other Plugins
All remaining plugins are used in their **original, unmodified** form.

---

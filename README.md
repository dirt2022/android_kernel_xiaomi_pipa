---

# Xiaomi Pad 6 (pipa) Kernel

**Android kernel for Xiaomi Pad 6 (codename: pipa).**

I will be maintaining this on a **best-effort basis** — updates happen when they happen.

> ⚠️ **IMPORTANT:** This kernel is only compatible with **MIUI firmware**. It has been tested on **MIUI 14.3 (China stock ROM)**. Do **NOT** use on HyperOS or other firmware.

---

## Known Issues

- None currently known.

---

## Changes from Stock

- Upgraded **aw882xx** audio driver to **version 2.0**

---

## Building & Flashing

Follow the standard Android kernel build procedure.

**Make sure you use the correct defconfig:**

```bash
make pipa_custom_defconfig
```

> **Note:** `pipa_user_defconfig` is preserved for reference/compatibility but **not recommended**. Use `pipa_custom_defconfig` for full hardware support (WiFi, touch, audio, etc.).

---

## Disclaimer

This is provided **as-is**. No guarantees, no warranties. Use at your own risk.

---

## Credits

- Based on UCMI kernel source

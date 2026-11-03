<h1 align="center"><span style="color: #00ffcc;">BitFlipper</span></h1>

<p align="center">
  A lightweight MicroPython port of Flipper Zero features for the micro:bit v1.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue" alt="Version">
  <img src="https://img.shields.io/badge/platform-micro:bit%20v1-red" alt="Platform">
  <img src="https://img.shields.io/badge/language-MicroPython-yellow" alt="Language">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

---

## <span style="color: #00ffcc;">Features</span>

*   **J (Jammer):** Broadcasts noise across 2.4GHz radio channels to interfere with local Wi-Fi and Bluetooth signals.
*   **R (Radar):** Scans 2.4GHz channels and displays signal strength using the LED matrix. One bar is a weak signal, five bars is a strong signal.
*   **P (Password):** Generates an 8-character password containing uppercase letters, lowercase letters, numbers, and special characters.

## <span style="color: #00ffcc;">Controls</span>

*   **Button B:** Scroll through modes.
*   **Button A:** Start or stop the selected mode.
*   **Button A (While generating password):** Cancel the generation and return to the menu.

## <span style="color: #00ffcc;">Installation</span>

1. Go to [python.microbit.org](https://python.microbit.org).
2. Paste the contents of `main.py` into the editor.
3. Click **Send to micro:bit**.

> [!WARNING]  
> This software is for educational purposes and hardware testing only. Do not use the jammer to cause malicious interference or disrupt networks you do not own.

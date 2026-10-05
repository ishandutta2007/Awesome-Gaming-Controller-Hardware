# Awesome-Gaming-Controller-Hardware

# Awesome-Gaming-Controller-Hardware

**Curated List of Commercial Controllers & Open-Source Firmware Projects**
*Focused on Hall Effect Sticks, Back Paddles, Trigger Stops & Custom Firmware*
**Last updated: October 2026**

This repository tracks notable **gaming controller hardware** and **open-source firmware projects** that maximize their potential. These tools help competitive gamers choose the right pro-grade controller and unlock advanced features with community-driven firmware.

**Examples** include Xbox Wireless Controller, DualSense Wireless Controller, Nintendo Switch Pro Controller, 8BitDo Ultimate, Razer Wolverine V3 Pro, Scuf Instinct Pro, PowerA Enhanced Wired Controller, Logitech F310, SteelSeries Stratus+, and GuliKit KingKong 2 Pro (the category leaders).

**Open-source emphasis**: The open-source controller ecosystem is **mature and production-proven**. **GP2040-CE** leads as the de-facto open-source gamepad firmware for Raspberry Pi Pico and RP2040 boards with **2,536 GitHub stars** and **674 forks** . **InputPlumber** is the open-source input router and remapper daemon for Linux with **239 stars**, popular among Linux handheld gaming devices . **AntiMicroX** provides graphical keyboard-to-gamepad mapping with **2,805 stars** and active development . **OpenSplitDeck** is a fully open-source hardware and firmware Steam Controller-inspired modular controller with **167 stars** .

## 📖 Table of Contents

- [🎮 Commercial Controllers](#-commercial-controllers)
- [🔓 Open-Source Firmware Projects](#-open-source-firmware-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 🎮 Commercial Controllers

> **📊 Market Context**: The global gaming controller market is estimated at **~$8B in 2026**, growing toward **~$15B by 2032**. The sector is **moderately fragmented** — **Microsoft**, **Sony**, and **Nintendo** dominate first-party controllers, while **8BitDo**, **Razer**, **Scuf**, and **GuliKit** lead the third-party premium and enthusiast tiers. **Pricing varies dramatically**: budget wired controllers like the **PowerA Enhanced Wired Controller** are **$16.99–$27.99** , the **Logitech F310** is **~$25–$30**, and the **Xbox Wireless Controller** is **$55–$69.99** for standard editions or **$79.99** for the X25 Special Edition . Premium pro controllers range from **$169.99** for the **Scuf Instinct** to **$249.99** for the **Razer Wolverine V3 Pro 8K** . **Hall Effect sticks** (drift-free magnetic sensors) are now standard on third-party premium controllers like the **GuliKit KingKong 2 Pro** and **8BitDo Ultimate** . No single vendor holds a winner-take-all position.

| Controller | Description | Pricing (Starting Tier) | Key Features | Company Size |
|------------|-------------|------------------------|--------------|--------------|
| **[Xbox Wireless Controller](https://www.xbox.com/en-US/accessories/controllers/xbox-wireless-controller)** | **The default PC and Xbox gamepad.** Bluetooth and USB-C connectivity, textured grips, hybrid D-pad. | **$55.54–$69.99** (standard) . **X25 Special Edition**: **$79.99** (October 20, 2026) . | Bluetooth + USB-C, textured triggers, hybrid D-pad, 3.5mm audio jack, Xbox/PC/Android/iOS compatibility . | **~$281B revenue (Microsoft FY2025)** |
| **[DualSense Wireless Controller](https://direct.playstation.com/)** | **Sony's PS5 controller with haptic feedback and adaptive triggers.** | **₹5,265–₹6,390** (~$65–$80) . **Limited Editions**: **$84.00** . | Haptic feedback, adaptive triggers, built-in microphone, 3.5mm jack, PS5/PC/Mac/Mobile compatibility . | **~$30B gaming revenue (Sony FY2025 est.)** |
| **[Nintendo Switch Pro Controller](https://www.nintendo.com/)** | **Nintendo's premium controller with HD rumble and amiibo support.** | **$32.00–$69.99** (new) . **Zelda TOTK Edition**: **$69.99** . | HD rumble, motion controls, amiibo NFC, 40-hour battery, Switch/Switch OLED/PC compatibility . | **~$12B revenue (Nintendo FY2025 est.)** |
| **[8BitDo Ultimate](https://www.8bitdo.com/)** | **Third-party premium with Hall Effect sticks and charging dock.** | **$66.48–$97.62** (Bluetooth) . **Ultimate 3**: **$99.99** . **Ultimate 3E**: **$149.99** (late Oct 2026) . | Hall Effect sticks (drift-free), charging dock, Bluetooth + 2.4G + wired, Switch/PC/Steam Deck/Android/iOS compatibility . | **Private (8BitDo)** |
| **[Razer Wolverine V3 Pro](https://www.razer.com/)** | **Competitive pro controller with TMR sticks and 8K polling.** | **$169.99–$249.51** . **Woot**: **$109.99** (45% off) . | TMR thumbsticks with swappable caps, 8,000 Hz polling rate, 6 remappable buttons, fast triggers, 36-hour battery, Xbox/PC compatibility . | **~$1.5B revenue (Razer FY2025 est.)** |
| **[Scuf Instinct Pro](https://www.scufgaming.com/)** | **The competitive standard for Xbox and PC.** Four embedded rear paddles, instant triggers. | **$219.99** (base) . **Newegg**: **$229.99–$329.00** . **Amazon (used)**: **~£163.90** . | 4 embedded remappable paddles (16 functions), instant triggers, interchangeable thumbsticks, 3 onboard profiles, non-slip grip . | **Part of Corsair** |
| **[PowerA Enhanced Wired Controller](https://www.powera.com/)** | **Budget wired controller for Xbox and Switch.** | **$16.99–$27.99** . **India**: **₹2,584–₹2,899** . | Two mappable Advanced Gaming Buttons, 3.5mm audio jack, 10ft detachable cable, officially licensed for Xbox/Switch . | **Private (PowerA)** |
| **[Logitech F310](https://www.logitech.com/)** | **Reliable budget PC gamepad with console-like layout.** | **$25–$30** (India: **₹1,334–₹2,595**) . | Console-like layout, 4-switch D-pad, 1.8m cord, PC/Steam/Windows/Android TV compatibility . | **~$1.5B revenue (Logitech FY2025 est.)** |
| **[SteelSeries Stratus+](https://steelseries.com/)** | **Mobile and PC controller with Hall Effect sensors.** | **$59.99–$69.99** MSRP . **Sale**: **$15–$25** (third-party) . | Hall Effect sensors, clickable L3/R3, Bluetooth, Android/Chromebook/PC compatibility, slim phone mount included . | **Private (SteelSeries)** |
| **[GuliKit KingKong 2 Pro](https://www.gulikit.com/)** | **First wireless controller with Hall Effect sensing joysticks.** | **$69–$99.99** . | Patented electromagnetic sticks (no drift), 1000Hz wired / 160Hz Bluetooth polling, NFC/amiibo support, Switch/PC/Android/iOS compatibility . | **Private (GuliKit)** |

## 🔓 Open-Source Firmware Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE)** — **The de-facto open-source gamepad firmware.** **2,536 stars, 674 forks, MIT license** . Multi-platform gamepad firmware for **Raspberry Pi Pico and other RP2040 boards** . Combines multi-platform compatibility (**PC, PS3, PS4, PS5, Nintendo Switch/Switch 2, Xbox 360/One/Series, Steam Deck, MiSTer, Android, Raspberry Pi**) with high performance and a rich feature set . Supports **analog inputs**, **ESP32-C3 BLE**, and custom arcade configurations . **Actively maintained** (updated September 26, 2026) . | [![Stars](https://img.shields.io/github/stars/OpenStickCommunity/GP2040-CE?style=social&color=white)](https://github.com/OpenStickCommunity/GP2040-CE/stargazers) | ~2,536 |
| **[InputPlumber](https://github.com/ShadowBlip/InputPlumber)** — **Open-source input router and remapper daemon for Linux.** **239 stars, GPL-3.0** . Combines any number of input devices (**gamepads, mice, keyboards**) and translates their input to various virtual device formats . **Key features**: Combine multiple input devices, emulate mouse/keyboard/gamepad inputs, intercept and route input over DBus, input mapping profiles, route input over the network . **Particularly popular among Linux gaming handhelds** (Lenovo Legion Go 2, MSI Claw, GPD Win Mini) . **Active development** (v0.81.0, September 2026) . | [![Stars](https://img.shields.io/github/stars/ShadowBlip/InputPlumber?style=social&color=white)](https://github.com/ShadowBlip/InputPlumber/stargazers) | ~239 |
| **[AntiMicroX](https://github.com/AntiMicroX/antimicrox)** — **Graphical program to map keyboard buttons and mouse controls to a gamepad.** **2,805 stars, 158 forks, GPL-3.0** . Useful for playing games with no gamepad support . **Features**: Switchable profiles, stick/pad/gyroscope input, haptic feedback, controller mapping for Xbox, PlayStation, Switch Pro, and generic gamepads . **Supports Windows, Linux, SteamOS, and Steam Deck** . **v3.6.1** released May 22, 2026 . **C++ based** . | [![Stars](https://img.shields.io/github/stars/AntiMicroX/antimicrox?style=social&color=white)](https://github.com/AntiMicroX/antimicrox/stargazers) | ~2,805 |
| **[OpenSplitDeck](https://github.com/tommybee456/OpenSplitDeck)** — **Fully open-source, modular wireless Steam Controller-inspired gamepad.** **167 stars** . **Custom modular wireless controller** inspired by Steam Deck and Steam Controller . **Features**: Trackpads, detachable halves, full HID support, nRF52840 microcontrollers, Enhanced ShockBurst protocol . **Custom-built trackpads** using Azoteq IQS7211E sensor . **Magnetic pogo-pin charging** and attachment system . **Emulates a DS4 controller** for Steam Input compatibility . **Gyro support** (one gyroscope in each half) . **3D-printable case** . **Fully open-source hardware and firmware** . **Early development stage (v0.3)** . | [![Stars](https://img.shields.io/github/stars/tommybee456/OpenSplitDeck?style=social&color=white)](https://github.com/tommybee456/OpenSplitDeck/stargazers) | ~167 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[xpadneo](https://github.com/atar-axis/xpadneo)** — Advanced Linux driver for Xbox One/Series controllers over Bluetooth. Fixes rumble, battery reporting, and connection issues . |
| **[DS4Windows](https://github.com/Ryochan7/DS4Windows)** — Windows tool for using DualShock 4 and DualSense controllers as Xbox 360 controllers. Remapping, profiles, and touchpad support . |
| **[BetterJoy](https://github.com/Davidobot/BetterJoy)** — Allows Nintendo Switch Pro Controller and Joy-Cons to be used as Xbox controllers on PC . |
| **[Steam Input](https://store.steampowered.com/)** — Built into Steam, supports extensive controller remapping, profiles, and gyro configuration for any controller. |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Controllers are **commercial hardware**; open-source firmware can extend functionality but may void warranties and carries risk of bricking devices.
- **Open-source reality**: The open-source ecosystem for gaming controllers is **mature and production-proven**. **GP2040-CE** is the de-facto firmware for RP2040-based DIY controllers with **2,536 stars** . **InputPlumber** provides Linux input routing for handhelds with **239 stars** . **AntiMicroX** delivers graphical keyboard-to-gamepad mapping with **2,805 stars** and active development . **OpenSplitDeck** demonstrates that fully open-source modular controller hardware is achievable with **167 stars** . However, **commercial controllers** (Xbox Elite, Scuf Instinct Pro, DualSense Edge) provide **polished hardware engineering, premium build quality, and dedicated support** that DIY alternatives may lack. The open-source path is **genuinely viable** for DIY builders, fightstick enthusiasts, Linux handheld users, and anyone willing to trade polish for full control.

---

**Made for competitive gamers, DIY controller builders, Linux gaming enthusiasts, and fightstick modders.**
Let's make gaming controllers more open, customizable, and repairable.

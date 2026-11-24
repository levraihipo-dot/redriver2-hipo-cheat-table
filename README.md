
# 🚔 Redriver 2 — Cheat Table v1.4.0

> **A Cheat Engine table for Redriver 2, focused on police behavior, pursuit mechanics, vehicle customization, and advanced game modifications.**

---

## ⚠️ Legal & Ethical Disclaimer

- This cheat table is intended **for single-player use only**. It has no impact on any multiplayer or online system.
- **Redriver 2 is a fan-made PC port** of the original Driver 2 (PS1), and is no longer commercially sold. This table does not interfere with any active commercial product.
- Use at your own risk. **Always back up your save files** before using any cheat table.
- Partial credit goes to **MrSam** for his original cheat table, portions of which were reused and built upon in this project. Full respect to his work — see credits below.

---

## 📋 Requirements

### 1. Redriver 2 (correct version required)

This cheat table is only compatible with the **latest up-to-date version of Redriver 2**, built via [Appveyor](https://ci.appveyor.com), using **MrSam's `.exe`**.

> 📥 **Download the compatible version here:** [redriver2-recommanded-build](https://github.com/levraihipo-dot/redriver2-hipo-build)

Using an older or different build will likely cause the table to not work or behave unexpectedly.

---

### 2. Cheat Engine

Cheat Engine is required to load and use this table.

> ⚠️ **Important warning about Cheat Engine installers:**
>
> The official Cheat Engine installer may bundle third-party offers. During installation, carefully review every step and decline any unwanted optional software.
>
> 🔍 It is strongly recommended to look up how to safely download and install Cheat Engine before proceeding (e.g. using the standalone/portable version, or verifying the source).
>
> **No direct link is provided here intentionally**, to encourage you to verify the source yourself.

---

# ✨ Features — v1.4.0

The v1.4.0 release introduces a **complete redesign of the cheat table**, with a new category-based organization, several new scripts, rewritten existing features, and an advanced custom police lighting system.

The table is now divided into four main categories:

- **Mr Sam's General Game Settings**
- **Simple Scripts**
- **Pursuit Scripts**
- **Custom Scripts**

---

## ⚙️ Mr Sam's General Game Settings

A collection of useful general game settings and quality-of-life modifications, designed to make gameplay adjustments easier and save time.

This category is based on **MrSam's original cheat table**.

> 🙏 Full credit to MrSam for this section and his original work.

---

## 🛠️ Simple Scripts

A collection of standalone scripts providing additional control over vehicles, police behavior, and visual effects.

### 🔇 Disable Cop Siren Sound for Player

Disables police siren sounds for the player's vehicle.

### 🚔 Spawn Player with Cop Handling

Applies police vehicle characteristics to the player's vehicle, including:

- Police hubcaps.
- Police exhaust smoke behavior.
- Police handling and physics.

> ⚠️ **DEV FEATURE:** This script is still under development and may cause bugs during vehicle spawning. Use with caution.

### 🚗 No Visual Damage on Pursuers

Prevents pursuer vehicles from displaying visual damage, keeping police vehicles looking clean even during intense pursuits.

### 🔍 Always High Level of Detail

Forces vehicles to maintain a high level of visual detail.

> ⚠️ Originally from MrSam's work. This script may cause game crashes. Use with caution.

### 🔄 Reset Vehicles

Resets vehicle slots **1–19** by setting their vehicle type to `0`.

Useful for resetting vehicle slots and clearing unwanted vehicle configurations.

---

## 🚨 Pursuit Scripts

Dedicated scripts for modifying police AI, pursuit behavior, police spawning, and overall difficulty.

### 🚗 All Vehicles Are Police Cars

Completely rewritten for v1.4.0.

This feature was already present in previous releases, but has now received a major code overhaul to improve reliability, stability, and flexibility.

Features include:

- Rewritten and reorganized script structure.
- Improved reliability.
- Real-time adjustable variables.
- Greater control over how many vehicles are affected.
- Support for up to 19 vehicle slots.

### 🎯 Cops Target Tanner

Modifies police targeting behavior, making police officers specifically target Tanner.

### 🎲 Random Cop Number and Spawn

Randomizes police vehicle numbers and spawning behavior, making each pursuit less predictable.

### 🎲 Random Police Difficulty

Randomizes police difficulty to create varying pursuit intensity.

### ⚡ Extreme Fast Cop Cheats

A collection of extreme-speed police modifications designed to make pursuits significantly faster and more intense.

---

## 🎨 Custom Scripts

Advanced custom modifications that go beyond standard cheat table functionality.

### 🚨 Custom Light Animation System [GYRO]

**A major custom system — developed over more than a month.**

GYRO is an advanced, highly customizable police lighting animation system, designed from the ground up to provide extensive control over emergency vehicle lighting.

After more than a month of development, testing, and reliability improvements, the system can finally operate across **all 19 vehicle slots simultaneously**, without interfering with the lighting systems of other vehicles.

**Main features:**

- **19 simultaneous vehicles** — Independent lighting animations across all 19 vehicle slots.
- **Independent RGB turn signals** — Fully customizable RGB lighting behavior.
- **Custom night lights** — Dedicated night lighting behavior.
- **Custom reverse lights** — Independent reverse light animations.
- **Thousands of possible combinations** — A huge variety of lighting configurations.
- **Dynamic animation patterns** — Lighting patterns are generated to avoid repeating the same combination twice.
- **Independent light animations** — Every individual light element has its own animation.
- **Vehicle-specific control** — Each vehicle maintains its own independent lighting behavior.

Unlike a conventional police light toggle, GYRO provides a complete vehicle-specific animation system, allowing multiple vehicles to display completely different lighting behaviors at the same time.

This is one of the biggest custom additions in v1.4.0.

### 🚧 Toggle Vehicle v27 [Roadblock-Like]

A custom system designed to reproduce the behavior of Roadblock vehicles, with additional customization and interaction possibilities.

**What's new:**

- Recreates Roadblock-like vehicle behavior.
- Police vehicles can now both **trigger AND stop** the behavior.
- New interaction possibilities between police vehicles.
- Police vehicles can be stopped by physically touching them, depending on the configured behavior.

This provides more control over police vehicle interactions and allows for more dynamic roadblock-like situations.

### 👮 Be A Cop

Take the role of a police officer and experience Redriver 2 from the perspective of law enforcement.

This script builds upon the heavily modified pursuit system introduced in v1.1.0, with police-oriented behavior and player physics.

> ⚠️ **IMPORTANT: PLEASE READ THE READ ME FILE BEFORE ACTIVATING THIS SCRIPT.**
>
> This feature modifies several gameplay systems. Make sure you understand its behavior and requirements before enabling it.

---

## 🙏 Credits

- **MrSam & contributors** (SoapyMan, Fireboyd78, 50thomatoes50, andre-vm, Rosalie241, Faalagorn, alotlikebeans) — For the original Redriver2 project and cheat table. Portions of MrSam's work were reused and built upon in this table. Huge thanks and respect for their work.
- **OpenDriver2 / REDRIVER2 project:** [GitHub Repository](https://github.com/OpenDriver2/REDRIVER2)
- **Compatible build:** [redriver2-hipo-build](https://github.com/levraihipo-dot/redriver2-hipo-build)

---

## 📜 Changelog

### v1.4.0

- **Major Update: Complete Cheat Table Overhaul** — Entire table redesigned and reorganized into four dedicated categories.
- **New: Mr Sam's General Game Settings** — Integrated useful general game settings from MrSam's original cheat table.
- **New: Simple Scripts Category** — Added Disable Cop Siren Sound for Player, Spawn Player with Cop Handling, No Visual Damage on Pursuers, Always High Level of Detail, and Reset Vehicles.
- **Updated: All Vehicles Are Police Cars** — Completely rewritten for improved reliability, with real-time adjustable variables and support for up to 19 vehicle slots.
- **New: Cops Target Tanner** — Police targeting modification.
- **New: Random Cop Number and Spawn** — Randomized police count and spawning.
- **Updated: Random Police Difficulty** — Included in the new Pursuit Scripts category.
- **New: Extreme Fast Cop Cheats** — Extreme-speed police modifications.
- **New: Custom Light Animation System [GYRO]** — Advanced independent RGB lighting animations, night lights, reverse lights, and thousands of possible combinations. Supports all 19 vehicle slots simultaneously without interfering with other vehicles.
- **Updated: Toggle Vehicle v27 [Roadblock-Like]** — Expanded roadblock-like behavior, including the ability for police vehicles to trigger and stop the behavior.
- **Updated: Be A Cop** — Included in the new Custom Scripts category. Read the README before activation.

### v1.1.0

- **New: Be a Cop mode** — Take the role of a police officer with a heavily modified pursuit system (based on MrSam's code). Supports all vehicle types, damage thresholds, no horn required, police physics for the player, and compatibility with All Vehicles Are Police Cars.
- **Updated: All Vehicles Are Police Cars** — Fixed timer duplication bug that caused crashes; script restructured for clarity; added **Vehicle Count** variable field (0–18) to control how many vehicles are affected.

### v1.0.0

- Initial release.
- All Vehicles Are Police Cars.
- Maximum Aggressive Police Difficulty.
- Random Police Difficulty.
- Aggressive On-Foot Police (PS1 behavior).
- Random Police Count & Spawn Rate.
- L2/R2 Trigger Control (pre-alpha, requires external Python script).
- Spawn as Police Car with Police Physics.

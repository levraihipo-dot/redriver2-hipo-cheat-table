# 🚔 Redriver 2 — Cheat Table v1.4.0

> **A Cheat Engine table for Redriver 2, focused on police behavior, difficulty, and vehicle mechanics.**

---

## ⚠️ Legal & Ethical Disclaimer

- This cheat table is intended **for single-player use only**. It has no impact on any multiplayer or online system.
- **Redriver 2 is a fan-made PC port** of the original Driver 2 (PS1), and is **no longer commercially sold**. This table does not interfere with any active commercial product.
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
> The official Cheat Engine installer **bundles adware** by default. During installation, you will be prompted to install unwanted third-party software — **always decline every optional offer**.
>
> 🔍 It is strongly recommended to look up how to safely download and install Cheat Engine before proceeding (e.g. using the standalone/portable version, or verifying the source). A quick search for *"how to install Cheat Engine safely"* will point you in the right direction.
>
> **No direct link is provided here intentionally**, to encourage you to verify the source yourself.

---

## ✨ Features — v1.1.0

### 🚗 All Vehicles Are Police Cars
Every vehicle in the game is replaced by a police AI. Maximum chaos, maximum fun.

Now with a **Vehicle Count** field — set a value between 0 and 18 to control exactly how many vehicles are affected. Timer and stability issues from v1.0.0 have been fixed.

---

### 🚔 Be a Cop *(New in v1.1.0)*
Take on the role of a police officer. Based on MrSam's cheat table code, this script includes a heavily modified version of "Pursuers Can Target Anyone":

- No need to honk anymore — just hitting a vehicle triggers a pursuit
- Works with all vehicle types except police (civilians and parked vehicles included); previously only moving vehicles were supported
- Vehicles with 20,000+ damage cannot be targeted for pursuit
- The player no longer needs to be in a police vehicle to trigger and conduct pursuits
- Non-police vehicles with police AI (marked as Patrolling) can also join pursuits — combine with **🚗 All Vehicles Are Police Cars** to enable them
- Player physics are replaced with police physics, and more

---

### 😤 Maximum Aggressive Police Difficulty
Sets police aggression to the highest possible value **just before** the threshold where their behavior breaks and they stop chasing you. The sweet spot for the most intense pursuit experience.

---

### 🎲 Random Police Difficulty
Randomizes police difficulty for unpredictable and varied pursuit intensity across sessions.

---

### 👮 Aggressive On-Foot Police (PS1 Behavior)
Restores the on-foot police aggression behavior from the original **PS1 version** of Driver 2, making cops far more aggressive when you're out of your vehicle.

---

### 🎲 Random Police Count & Spawn Rate
Randomizes both the number of police units and their spawn rate, keeping every chase feeling fresh and different.

---

### 🎮 L2 / R2 Trigger Vehicle Control *(Pre-Alpha)*
Enables using **L2 and R2 triggers** for vehicle control (acceleration/brake).

> ⚠️ **Pre-Alpha feature** — This was implemented as a proof-of-concept to test feasibility. It requires a **separate Python script that is not included** in this release and is not yet publicly available. **Do not expect this to work out of the box.** It will be properly developed and released in a future version.

---

### 🚔 Spawn as a Police Car (with Police Physics)
Spawn your vehicle as a police car with full police physics applied:
- No hubcap loss
- No drift smoke
- Behavior nearly identical to the in-game police AI vehicles

---

## 🙏 Credits

- **MrSam & contributors** (SoapyMan, Fireboyd78, 50thomatoes50, andre-vm, Rosalie241, Faalagorn, alotlikebeans) — For the original Redriver2 project and cheat table. Portions of MrSam's work were reused in this table. Huge thanks. [OpenDriver2/REDRIVER2](https://github.com/OpenDriver2/REDRIVER2)
- **Compatible build** available here: [redriver2-hipo-build](https://github.com/levraihipo-dot/redriver2-hipo-build)

---

## 📜 Changelog

Voici un changelog en anglais, dans le même style que tes versions précédentes, avec une présentation structurée et professionnelle pour la version 1.4.0.

Écriture

# v1.4.0

### Major Update — Complete Cheat Table Overhaul

- **Complete Cheat Table Redesign** — The entire cheat table has been rebuilt and reorganized into dedicated categories for better navigation, clarity and usability.

### Mr Sam's General Game Settings

- **New Category: Mr Sam's General Game Settings** — Includes useful game settings and quality-of-life cheats designed to save time and improve the overall experience.
  - Based on Mr Sam's original cheat table. Full credit to him for this section.

### Simple Scripts

- **New Category: Simple Scripts** — Several new standalone scripts have been added:
  - **Disable Cop Siren Sound for Player** — Disables police siren sounds for the player's vehicle.
  - **Spawn Player with Cop Handling** — Gives the player's vehicle police hubcaps, exhaust smoke and police handling/physics. _(DEV – May cause bugs during vehicle spawning.)_
  - **No Visual Damage on Pursuers** — Prevents pursuer vehicles from displaying visual damage.
  - **Always High Level of Detail** — Forces vehicles to maintain a high level of detail. _(From Mr Sam – May cause game crashes.)_
  - **Reset Vehicles** — Resets vehicle slots 1–19 by setting their type to 0.

### Pursuit Scripts

- **All Vehicles Are Police Cars** — Completely rewritten and improved for increased reliability and stability. Now features real-time adjustable variables for greater control over the system.
- **Cops Target Tanner** — New script that makes police officers specifically target Tanner.
- **Random Cop Number and Spawn** — Randomizes police vehicle count and spawning behavior.
- **Random Police Difficulty** — Randomizes police difficulty.
- **Extreme Fast Cop Cheats** — New extreme-speed police cheats for a more intense pursuit experience.

### Custom Scripts

- **NEW: Custom Light Animation System \[GYRO\]** — An advanced, highly customizable police lighting system that took over a month of development, testing and optimization to finally achieve reliable operation.
  - Supports all **19 vehicle slots simultaneously** without interfering with the lights of other vehicles.
  - Independent RGB turn signals.
  - Custom night lights and reverse lights.
  - Thousands of possible lighting combinations.
  - Never repeats the same lighting pattern twice.
  - Every individual light element has its own independent animation, separately controlled for each vehicle.
  - A fully independent, vehicle-specific lighting animation system.
- **Toggle Vehicle v27 \[Roadblock-Like\]** — Recreates the behavior of Roadblock vehicles with additional customization options.
  - Police vehicles can now both trigger AND stop the roadblock behavior.
  - New interaction possibilities, including stopping a police vehicle by physically touching it.
  - More control over police vehicle behavior and interactions.
- **Be A Cop** — Take control of the police role and experience the game from the perspective of a police officer.
  - **IMPORTANT: Please read the READ ME file before activating this script.**


### v1.1.0
- **New: Be a Cop mode** — Take the role of a police officer with a heavily modified pursuit system (based on MrSam's code). Supports all vehicle types, damage thresholds, no horn required, police physics for the player, and compatibility with All Vehicles Are Police Cars
- **Updated: All Vehicles Are Police Cars** — Fixed timer duplication bug that caused crashes; script restructured for clarity; added **Vehicle Count** variable field (0–18) to control how many vehicles are affected

### v1.0.0
- Initial release
- All Vehicles Are Police Cars
- Maximum Aggressive Police Difficulty
- Random Police Difficulty
- Aggressive On-Foot Police (PS1 behavior)
- Random Police Count & Spawn Rate
- L2/R2 Trigger Control (pre-alpha, requires external Python script)
- Spawn as Police Car with Police Physics

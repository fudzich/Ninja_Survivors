# 🥷 Ninja City

> A fast-paced, top-down 3D arena survival game built in Unity (C#) for the University of London CM3030 Games Development module.

[![Play on itch.io](https://img.shields.io/badge/Play%20on-itch.io-FA5C5C?logo=itch.io&logoColor=white)](https://jeremyf2020.itch.io/ninja-city) ![Language](https://img.shields.io/badge/Language-C%23-239120) ![Engine](https://img.shields.io/badge/Engine-Unity-black) ![Platform](https://img.shields.io/badge/Platform-WebGL-blue) ![Rating](https://img.shields.io/badge/Playtest%20Rating-4.95%2F5-brightgreen)

![Ninja City Gameplay Demo](./demo.gif)

🕹️ **[Play Ninja City in your browser on itch.io →](https://jeremyf2020.itch.io/ninja-city)**

## 💡 Overview

*Ninja City* is a 5-minute, pick-up-and-play single-player survival game set in a stylized low-poly Japanese city. Players battle escalating enemy waves across two difficulty modes (**Easy / Tutorial** and **Normal**), level up to unlock randomized skill upgrades, and endure a final **5-Boss Gauntlet**.

## 🎮 Gameplay & Controls

| Input | Action | Details |
| :--- | :--- | :--- |
| **`W` `A` `S` `D`** | Move | Responsive script-driven movement |
| **Left / Right Click** | Melee / Ranged | Katana slash & Shuriken throw aimed via mouse raycast |
| **`Space`** | Stealth | Drops enemy aggro (enemies switch to idle; contact still deals damage) |
| **`1`** | Fireball | High-damage ranged burst (scales projectile count per level) |
| **`2`** | Tornado | Channeled AoE summon with ground rune indicator |
| **`3`** | Heal | Restores HP to recover from high-pressure waves |

- **🔥 Hidden Elemental Combo:** Launching a **Fireball** into an active **Tornado** triggers a high-damage **Fire Tornado**.
- **👹 Final Boss Gauntlet (4:00 – 5:00):** Five oversized bosses spawn every 10 seconds with telegraphed **Roll** and **Fire Ring Spin** attacks, paired with dynamic boss BGM.

## ⚙️ Technical Highlights

- **Modular C# Architecture:** Refactored core systems around abstract base classes (`Status`, `ISkill`) to centralize health, cooldowns, and damage handling across multiple enemy tiers and boss states.
- **WebGL Performance Optimization:** Pivoted from heavy high-detail models to stylized low-poly 3D assets and standardized on a `4:3` aspect ratio for smooth browser performance and visual focus.
- **Playtest-Driven UX:** Iterated across three rounds of user surveys (final average rating: **4.95/5**; **95.2%** high learnability), introducing an auto-hiding tutorial guide, easing HP/EXP bars, and randomized skill level-ups to keep combat uninterrupted.

## 👥 Credits

Developed by **Team 11** (Ka Ming Fan, Vsevolod Zakharov, Josef Alkhuzanie) — BSc Computer Science, University of London.

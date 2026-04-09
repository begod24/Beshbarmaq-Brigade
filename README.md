# Beshbarmak Brigade

> **Helldivers meets mutant Kazakh cuisine.** A 2–4 player co-op top-down shooter where a squad of Kazakh fighters battles grotesque food-creatures that have invaded Kazakhstan from a parallel dimension.

---

## Overview

**Genre:** Top-Down Co-op Shooter  
**Players:** 2–4 (Online / LAN)  
**Engine:** Unity (URP)  
**Platforms:** PC (primary), Mobile-compatible architecture  
**Target Age:** 16+  
**Session Length:** 8–20 minutes per mission  

A failed dimensional ritual called the **Dastarkhan Collapse** fused food, folklore energy, and military bio-tech — spawning sentient culinary abominations led by **The Great Kazan**. The **Nomad Response Squad** deploys to close the rifts, rescue civilians, and eliminate the Kazan Generals.

---

## Key Features

- **Fast Arcade Co-op** — Drop in, fight through compact missions, extract. Easy to learn, hard to master.
- **Kazakh Cultural Identity** — Humor, folklore motifs, and recognizable traditional dishes turned into terrifying biomass monsters.
- **Helldivers-Inspired Gameplay** — Objective-based missions with extraction, team revives, shared lives, and escalating chaos.
- **Combo System** — Oil + fire, stun + crit, slow + explosive. Coordinate abilities for maximum damage.
- **Stylized Low-Poly Art** — Hand-painted look with saturated earthy palette. Readable silhouettes, optimized for low-spec hardware.
- **Replayability** — Random enemy mixes, difficulty modifiers, unlockable heroes, weapons, and cosmetics.

---

## Enemy Faction: The Brothborn

| Enemy | Role | Behavior |
|---|---|---|
| **Beshbarmak Brute** | Heavy Melee | Wide noodle-whip attacks, slow but devastating |
| **Kazy Roller** | Charger | Fast charging sausage beast |
| **Shuzhyk Spitter** | Ranged | Shoots grease projectiles from distance |
| **Baursak Swarmers** | Kamikaze | Tiny bouncing explosive enemies |
| **Manty Bomber** | Area Denial | Slow units that explode into steam clouds |
| **Tea Wraith** | Support | Buffs nearby monsters |
| **Lagman Crawler** | Control | Tentacle noodle enemies that root players |
| **Kurt Turret** | Artillery | Stationary salty growths |

**Bosses:** The Great Kazan (cauldron warlord), Qazy Khan (armored sausage knight), Lady Shorpa (summons broth pools), The Doughmaker (endless spawner).

---
## Gameplay Loop

```
Deploy → Clear Rooms → Complete Objectives → Extract → Earn Rewards → Upgrade → Next Mission
```

**Objective types:** Survive waves, escort generator carts, seal rift points, rescue civilians, carry artifacts, defend radio towers, boss eliminations.

**Progression:** Account level → Weapon unlock tree → Hero perks (2–3 per hero) → Cosmetics earned through gameplay. Currency: **Salt**.

---

## Missions

| # | Mission | Setting |
|---|---|---|
| 1 | Village of Steam | Tutorial zone, basic enemies |
| 2 | Market Panic | Chokepoints, explosive carts, civilians |
| 3 | Steppe Rift | Open field, charge enemies, weather hazards |
| 4 | The Broth Lab | Parallel-world sci-fi facility |
| 5 | Kazan Citadel | Boss chain and final fight |

---

## Tech Stack

- **Unity 6 LTS** with **URP**
- **New Input System** (dual PC + Mobile support)
- **Netcode for GameObjects / Photon Fusion / FishNet** (networking)
- **Cinemachine** (camera — fixed 35–55° top-down tilt)
- **Addressables** (content loading)
- **ScriptableObjects** (weapons, enemies, data-driven design)
- **Object Pooling** (performance)
- **Shader Graph** (wet organic materials, subsurface scattering)

**Targets:** 60 FPS on PC, 30 FPS on mobile. No complex physics, limited dynamic lights, baked shadows.

---

## MVP Scope

The first playable build includes:

- 1 biome, 1 map
- 2 heroes, 4 weapons
- 4 enemy types + 1 mini-boss
- 1 gadget
- Extraction loop
- Online or LAN co-op for 2 players
- Basic UI and HUD

---

## Roadmap

| Phase | Duration | Deliverables |
|---|---|---|
| Pre-production | 2–4 weeks | Pillars, pitch, moodboard, prototype map |
| Prototype | 4–8 weeks | Movement, shooting, enemy AI, co-op sync |
| Vertical Slice | 6–12 weeks | 1 polished mission, hero abilities, boss, menus |
| Content Production | Ongoing | More missions, variants, heroes, localization |
| QA / Soft Launch | — | Closed testing, Steam page, demo festival |
| Release | — | Patches, balance, content updates |

---

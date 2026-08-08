# CTB Stadium: Anime Battle Sim (WIP)

> **⚠️ DISCLAIMER:** *CTB Stadium is a free, non-profit fan project. It is strictly not affiliated with, endorsed, or sponsored by Nintendo, Game Freak, or The Pokémon Company. All related characters, names, and assets are property of their respective owners.*

**CTB Stadium: Anime Battle Sim** is a browser-based tactical battle simulator focused on competitive momentum and team mechanics. 

Engineered as a lightweight Progressive Web App (PWA), it bypasses traditional app stores. Players can install the game directly to their home screens for a native, fullscreen viewport. Thanks to dynamic Service Worker caching, all assets—including heavy GIF sprites—are stored locally, enabling fully offline same-device battles.

---

## ⚔️ Gameplay Overview

Unlike traditional battle simulators that restrict you to 4 moves, CTB Stadium opens up the entire playbook. It features a dynamic CTB combat system where **every character has access to 10+ distinct attacks and abilities** simultaneously, giving you total tactical control over their entire kit.

### ⚡ Move Categories & Economy
To balance having access to over a dozen options at once, every character's move pool is structured around three core categories:
* **Basic (Energy Generators):** Fast, reliable strikes and setup moves that generate the energy needed to trigger larger plays.
* **Advanced (High-Cost Nukes):** Powerful, expensive finishers (like *Earthquake*, *Stone Edge*, and *Outrage*) that consume pooled energy to deliver massive damage.
* **Tactics (Utility & Control):** Status ailments, heals, entry hazards, and defensive maneuvers (like *Softboiled*, *Stealth Rock*, and *Protect*) used to dictate the tempo of the battle.

### 🛡️ Playstyle Archetypes
With anywhere from 11 to 13 moves per character, each Pokémon features a tailored move distribution that defines its combat role:
* **Offensive Juggernauts:** Heavy hitters like **Garchomp** and **Tyranitar** packed with expensive **Advanced** moves to clean up weakened targets.
* **Fast Energy Generators:** Swift speedsters like **Weavile** featuring deep **Basic** move pools for rapid momentum generation.
* **Utility Walls:** Defensive anchors like **Blissey**, **Skarmory**, and **Umbreon** loaded with **Tactics** options to stall out hyper-offensive teams.

---

## ✨ Features
* **Massive Move Pools:** Access 10 to 13 moves per character without swapping.
* **Local Play:** Pass-and-play tactical battles on a single device.
* **Online PVP:** Peer-to-peer WebRTC matchmaking powered by PeerJS.
* **PWA Ready:** Installable to mobile home screens with full offline caching support.
* **High-Performance Visuals:** Smooth, hardware-accelerated CSS animations with floating damage numbers and animated sprite visuals.

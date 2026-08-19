# CTB Stadium: Anime Battle Sim

> **⚠️ DISCLAIMER:** *CTB Stadium is a free, non-profit fan project. It is strictly not affiliated with, endorsed, or sponsored by Nintendo, Game Freak, or The Pokémon Company. All related characters, names, and assets are property of their respective owners.*

**CTB Stadium: Anime Battle Sim** is a browser-based tactical battle simulator focusing more on the anime battle momentum and team mechanics. 

Engineered as a lightweight Progressive Web App (PWA), it bypasses traditional app stores. Players can install the game directly to their home screens for a native, fullscreen viewport. Thanks to dynamic Service Worker caching all assets, including heavy GIF sprites are stored locally, enabling fully offline same-device battles.

---

## ⚔️ Gameplay Overview

Unlike traditional battle simulators that restrict you to 4 moves, CTB Stadium opens up the entire playbook. It features a dynamic CTB combat system where **every character has access to 10+ distinct attacks and abilities** simultaneously, giving you total tactical control over their entire kit.

### ⚡ Move Categories & Economy
To balance having access to over a dozen options at once, every character's move pool is structured around three core categories:
* **Basic (Energy Generators):** Fast, reliable strikes and setup moves that generate the energy needed to trigger larger plays.
* **Advanced (High-Cost Nukes):** Powerful, expensive finishers (like *Earthquake*, *Stone Edge*, and *Outrage*) that consume pooled energy to deliver massive damage.
* **Tactics (Utility & Control):** Status ailments, heals, entry hazards, and defensive maneuvers (like *Softboiled*, *Stealth Rock*, and *Protect*) used to dictate the tempo of the battle.

### 🛡️ Playstyle Archetypes
With over 20+ moves per character, each Pokémon features a tailored move distribution that defines its combat role:
* **Offensive Juggernauts:** Heavy hitters like **Garchomp** and **Tyranitar** packed with expensive **Advanced** moves to clean up weakened targets.
* **Fast Energy Generators:** Swift speedsters like **Weavile** featuring deep **Basic** move pools for rapid momentum generation.
* **Utility Walls:** Defensive anchors like **Blissey**, **Skarmory**, and **Umbreon** loaded with **Tactics** options to stall out hyper-offensive teams.

---

## ✨ Features
* **Massive Move Pools:** Access 20+ moves per character without swapping.
* **Local Play:** Pass-and-play tactical battles on a single device.
* **Online PVP:** Peer-to-peer WebRTC matchmaking powered by PeerJS.
* **PWA Ready:** Installable to mobile home screens with full offline caching support.
* **High-Performance Visuals:** Smooth, hardware-accelerated CSS animations with floating damage numbers and animated sprite visuals.

---

## 🚀 What's New in v1.2 (The Campaign & Polish Update)

Version 1.2 introduces a massive single-player experience alongside critical upgrades to the engine's AI, combat math, and mobile responsiveness.

### 🏆 Single Player Stadium Campaign
* **Campaign Mode:** Challenge a 13-stage offline PvE campaign featuring 8 Gym Leaders, the Elite Four, and the Champion. 
* **Thematic Boss AI:** Each boss features a pre-constructed thematic draft (e.g., Weather, Terrain, Stall, Hyper-Offense) with progressive AI aggression.
* **Hall of Fame:** Defeating the Champion generates a dynamic, shareable "Certificate of Triumph" to commemorate your victory.

### 🧠 Smarter CPU AI
* **Protect Awareness:** The AI is designed to predict baits and stall tactics, providing a very high yet dynamic difficulty progression.
* **Kill Securing:** Fixed execution math to ensure the AI properly leverages priority moves (like *Quick Attack* or *Bullet Punch*) when an enemy is at low HP.

### 🛠️ Engine & UI Fixes
* **Mobile Viewport Lock:** Upgraded the app container to utilize `100dvh` and strictly locked touch-scaling, completely preventing the UI from bouncing or clipping behind mobile browser URL bars.
* **Turn Order panel Stabilized:** Squashed fatal scope errors associated with Confusion self-damage, ensuring the timeline engine seamlessly processes volatile status effects without freezing.
* **Gluttony Fixed:** The Gluttony ability correctly doubles energy generation post-execution.
* **Now includes a Tutorial Guide:** Tutorial mode implemented to address the difficulty in learning CTB combat for newcomers.
* **Clean Exits:** Forfeiting a match or exiting the tutorial now flawlessly clears all high z-index overlays, preventing UI ghosting on the Main Menu and Win screens.

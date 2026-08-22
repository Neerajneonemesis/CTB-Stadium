# CTB Stadium: Anime Battle Sim

**CTB Stadium** is a fan-made, browser-based Pokémon battle simulator that completely replaces traditional round-based combat with a **Continuous Turn Battle (CTB)** Action Value (AV) timeline. 

Battles flow dynamically like they do in the anime: fast Pokémon can lap slower ones, heavy moves require charging, and managing your Action Value is just as important as managing your HP.

## 🌟 Key Features
* **The AV Timeline Engine:** Moves don't happen simultaneously. Every action costs Action Value (AV) based on its power and the user's Speed stat. Fast sweeps, delayed charges, and timeline manipulation dictate the meta.
* **Energy Economy:** Replaces PP. Pokémon must use low-power **Builders** to generate Energy before they can unleash high-power **Spenders** or setup moves.
* **100% Client-Side:** Built entirely in HTML, Tailwind CSS, and Vanilla JavaScript. No backend servers required.
* **Online PvP:** Seamless peer-to-peer multiplayer using **PeerJS**. 
* **PWA Ready:** Installable as a Progressive Web App to play offline or on mobile devices like a native app.
* **Anime-Style Presentation:** Dynamic hit sparks, screen shakes, UI pop-ups, and retro SFX for high-impact combat.

## 🎮 Game Modes
* **Stadium Campaign (1P):** A 13-boss gauntlet featuring Kanto Gym Leaders, the Elite Four, and the Champion. Features advanced AI that understands format-specific metas, entry hazards, and speed control. Saves your progress locally.
* **Quickplay (1P vs CPU):** Draft a custom team and fight against the AI in either Singles or Doubles.
* **Local PvP (2P):** Pass-and-play multiplayer on a single screen.
* **Online PvP:** Host or join a room via a simple 5-character room code to battle friends remotely.

## ⚔️ Formats & Meta
The engine dynamically adjusts rules and AI behavior based on the selected format:
* **VGC 2v2 (Doubles):** Focuses on spread damage, speed control (`Tailwind`, `Icy Wind`), and redirection (`Follow Me`, `Wide Guard`). 
* **Smogon 6v6 (Singles):** Focuses on a brutal war of attrition. The meta revolves around Entry Hazards (`Stealth Rock`, `Spikes`), Phazing (`Roar`, `Dragon Tail`) to bankrupt enemy energy, and safe pivots (`U-turn`, `Volt Switch`).

## ⚙️ Core Mechanics
* **Charge Delays:** Powerful moves (Advanced Spenders, Setup Buffs) enter a `⏳ CHARGING` phase. The Pokémon sits on the timeline while preparing the attack, leaving them vulnerable to fast priority strikes or evasive maneuvers.
* **Evasion Intercepts:** Tactical moves like `Detect` and `Double Team` instantly consume your turn but guarantee evasion against the very next incoming attack, serving as vital defensive tools against slow nukes.
* **Weather & Terrain Scaling:** Certain moves interact directly with the timeline. For example, `Solar Beam` charges 30% faster in Harsh Sunlight, and `Expanding Force` is cast 30% faster on Psychic Terrain.

## 🚀 Quick Start
CTB Stadium is 100% client-side. No servers, no databases, no heavy downloads.

* **Play Locally:** Download the files, keep `index.html`, `sw.js`, and `manifest.json` in the same folder, and open `index.html` in any web browser.
* **Play Online:** Host the folder for free on GitHub Pages, Vercel, or Netlify to generate a live link for Online PvP.
* **Go Mobile:** Because the engine is PWA-ready, opening your live link on an Android or iOS browser will prompt you to "Add to Home Screen"—turning it into a standalone mobile app!

## 📜 Disclaimer & Legal
**CTB Stadium is a non-profit, open-source fan project.** 
This simulator is created strictly for educational programming and entertainment purposes. It is not affiliated with, endorsed, sponsored, or specifically approved by Nintendo, Game Freak, or The Pokémon Company. All Pokémon images, names, and related media are intellectual property of their respective owners. No monetization, advertisements, or microtransactions exist within this project.

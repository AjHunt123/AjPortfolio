## Portfolio

---

### Project No#1: Astro Breaker — Precision Shooter

[Shooter Game](/sample_page)

**An arcade-style shooter built with Unity and C#.**  
This project focuses on responsive controls, dynamic difficulty scaling, and particle-based visual feedback. The player pilots a spacecraft at the bottom of the screen, dodging enemy projectiles while destroying waves of increasingly agile foes.

**Key features:**
- **Adaptive AI:** Enemies change formation and fire rates as the player's score increases.
- **Power-up system:** Temporary boosts include spread shot, shield, and slow-motion time.
- **Score chaining:** Consecutive hits multiply your score, encouraging aggressive play.
- **Audio integration:** Dynamic soundtrack layers intensify during boss encounters.

The game was developed over 8 weeks as part of a game mechanics course. It taught me how to manage finite state machines (FSM) for enemy behavior, optimize object pooling for projectiles, and implement a responsive UI that scales across resolutions.

<img src="images/project1.png?raw=true"/>
<img src="images/project1.2.png?raw=true"/>
<img src="images/project1.3.png?raw=true"/>
<img src="images/project1.4.gif?raw=true" width="500"/>

---

### Project No#2: Duskfall — Rogue-like Dungeon Crawler

[Rogue Like Game](/pdf/sample_presentation.pdf)

**A procedurally generated rogue-like dungeon crawler built in Unity.**  
This project explores permadeath mechanics, randomized loot tables, and turn-based tactical combat. Each playthrough offers a unique map layout, enemy placements, and item combinations — ensuring high replayability.

**Core systems implemented:**
- **Procedural level generation:** Uses a Binary Space Partitioning (BSP) algorithm to create branching dungeon rooms and corridors.
- **Loot & rarity system:** Weapons and relics have randomized stats (damage, crit chance, elemental effects) across four rarity tiers.
- **Permanent upgrades:** Between runs, players spend collected currency on account-wide buffs (health, stamina, starting items).
- **Save state management:** Permadeath with checkpoint-less design — death resets the run, but meta-progress is preserved.

This project was a deep dive into data persistence (PlayerPrefs + JSON serialization), randomization without breaking balance, and creating a satisfying risk/reward loop. I also learned to design modular enemy behaviors using scriptable objects.

<img src="images/project2.0.png?raw=true"/>
<img src="images/project2.1.png?raw=true"/>
<img src="images/project2.png?raw=true"/>
<img src="images/project2.4.gif?raw=true" width="500"/>

---

### 🧠 What I'm learning next
- Multiplayer networking using Mirror or Photon (for a co-op dungeon crawler prototype).
- Shader graph for real-time VFX (energy shields, portals, heat distortion).
- Version control best practices with Git LFS for game assets.

> *All projects shown are student works created for academic and portfolio purposes. Full source code is available upon request.*

---

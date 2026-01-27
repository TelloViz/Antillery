# Antillery

## ⚠️ Repository Access ⚠️

> This is a public-facing showcase repo. The full game source and assets are private due to ongoing commercial development.
> If you are reviewing this for hiring, I can provide a guided walkthrough of the architecture and key systems, and share limited code excerpts on request.

---

## What is Antillery?

Antillery is a 2D turn-based artillery game where teams of ants battle across deformable terrain using both destructive weapons and unconventional tools of peace.

Fire rockets. Plant sunflowers. Roll out sod. Every move alters the battlefield.

Designed for local multiplayer (2–4 players), Antillery blends strategic chaos with environmental satire. Explosions reshape the terrain. So do wildflowers.

No two matches play the same. No tool is ever just what it seems.

---

## Core Features

- **Physics-based turn combat**  
  Launch projectiles influenced by gravity, wind, and terrain deformation.

- **Peace tools that disrupt**  
  Plant sunflowers, roll sod, and deploy butterflies. Block, trap, deflect.

- **Destructible + constructible terrain**  
  The battlefield evolves as tools carve, patch, or redirect the flow of the match.

- **Couch multiplayer (2–4 players)**  
  Play on a single device with your friends.

- **Modular tool system**  
  Tools defined via ScriptableObjects. Easy to extend or rebalance.

- **Input abstraction layer**  
  Unity Input System with support for gamepads, keyboards, and custom bindings.

---

## Development Environment

- Built in **Unity (LTS)** using **C#**, with modular, decoupled architecture
- Uses the **Unity Input System** with per-player abstraction via custom interfaces
- Terrain defined as a **black-and-white alpha mask**, destructible and restorable in real time
- All gameplay tools (weapons and peace actions) defined via **ScriptableObjects**
- Turn system and game flow managed by layered **state machines**
- Includes custom dev tools for map generation, debug terrain editing, and prototype testing
- Designed for **offline-first, local multiplayer**, with optional future expansion for AI or online play

---

## Development Context

This project was developed as a solo Computer Science capstone at California State University, Fullerton. It blends traditional game development with modular software engineering and environmental satire.

Antillery is not a clone. It’s a reinterpretation. Tools of peace can cause just as much chaos as tools of war.

---

## Screenshots

<!-- Replace these with real images or GIFs when available
![Antillery Gameplay Placeholder](images/placeholder1.png)
![Tool Selection UI](images/placeholder2.png) -->

---

## License & Reuse

This repository is a public-facing showcase of Antillery. The full game source code and assets are private due to ongoing commercial development.

All rights to the core Antillery project, including code, assets, and design, are reserved. No permission is granted to copy, redistribute, or reuse any part of the project without explicit written consent.

If you are reviewing this for hiring, I can provide a guided walkthrough of the architecture and key systems, and share code excerpts or a limited sample module on request.

> Interested in collaborating or licensing? Contact me below.


---

## Contact

- 📧 lollisjosh@csu.fullerton.edu
- 🌐 [Project Page](https://lollisjosh.github.io/projects/antillery)

---

Thanks for checking out Antillery.

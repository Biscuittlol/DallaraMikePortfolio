# Michael A. Dallara

San Mateo, CA 94403 · 650-302-3109 · mikedallara2@gmail.com · [linkedin.com/in/mike-d-89a75274](https://www.linkedin.com/in/mike-d-89a75274)

## Professional Summary

Unity Developer with 8+ years of hands-on experience delivering interactive 3D applications for PC and VR platforms using C# and Unity Engine. Proven track record of building scalable systems, immersive simulations, AI behavior, and modular mechanics end-to-end. Extensive expertise in system logic design, including intelligent agent behavior, encounter design, and state-driven control systems. Successfully released multiple titles on Steam and independently prototyped complex RTS and RPG simulations.

## Core Skills & Technologies

- **Languages & Frameworks:** C#, .NET, OOP, Unity ShaderLab (HLSL)
- **Engines & Tools:** Unity (URP/LWRP), NavMesh, Timeline, Animator, Shader Graph
- **VR Platforms:** Oculus, HTC Vive, Valve Index, SteamVR, OpenXR
- **Gameplay & Logic Systems:** Finite State Machines, Behavior Trees, AI Encounters, Boss/Enemy Logic Design
- **Architecture & Prototyping:** Modular Architecture, OOP, Rapid Iteration, UI/UX, Simulation Logic
- **AI / LLM:** Anthropic Claude API, structured/constrained generation, agentic multi-step pipelines
- **Deployment Platforms:** Windows, SteamVR, Android
- **Version Control:** Git, PlasticSCM
- **Other Tools:** Blender (low-poly optimization), Visual Studio

## Selected Projects & Prototypes

### AI Runtime 3D Generator
- Built an LLM-driven Unity system that turns natural-language descriptions into structured, editable 3D models generated at runtime, with a deterministic C# geometry engine behind a constrained-output model for reproducible, verifiable results
- Engineered a two-pass agentic pipeline (build → paint) on the Anthropic Claude API, holding a calibrated prompt-to-engine contract across an open-ended domain (mechanical parts to full vehicles and structures)
- Produced a programmable, named object hierarchy per model and a data-driven asset lifecycle (save, deterministic re-spawn, duplicate, hand-edit, refine), with EditMode unit tests on the core geometry

### Crabbing Game (Fishing & Crabbing Simulation)
- Designed the core fishing combat as a real-time force model where fish pull, reel drag, line tension, break strength, and rod backbone all share one unit (pounds), so the fight balances on honest physics rather than difficulty constants
- Engineered a real-time rod-bend simulation (integrated quadratic bend arc shared by mesh and line renderers, decoupled bend depth/plane, fish-primary line-tether constraint) with a diegetic, load-weighted control scheme
- Architected a data-driven marine ecology (ScriptableObject species, daily terrain-raycast spawner, pooled/streamed schools) and a custom procedural-seafloor editor tool with domain-warped noise and non-destructive re-shaping

### Tactical RTS Prototype
- Designed and coded all systems: unit control, enemy AI, boss encounters, resource economy, and base management
- Engineered RTS input schemes, tactical formations, and advanced unit behaviors using FSMs and modular state logic
- Built scalable backend for unit stats, combat loops, upgrades, and progression

### RPG Potion & Goods Simulator
- Developed an interactive economy simulation with NPC bartering, randomized demands, and player-driven pricing
- Created a modular potion crafting system with multi-step interaction and farming-based ingredient production
- Implemented a building/placement system for customizable player workspaces and crafting stations

### Safari Hunter (Shipped Commercial VR Title)
- Programmed immersive weapon handling, puzzle triggers, and VR locomotion systems
- Built AI behaviors for 29 animal species (prey/predator) on an extensible state-machine framework with reactive design
- Optimized performance for large-scale environments with 100+ live entities, with rarity-weighted, ecology-aware spawning
- Integrated a full Steam/Oculus backend: achievements, save/load, leaderboard APIs

### LSAT Prep Simulator
- Built a complete standalone exam-prep desktop application in Unity/C# from scratch — data model, UI, test engine, scoring, and persistence
- Implemented a data-driven test engine that randomly assembles timed, multi-section exams from a typed question bank, plus an on-disk save/load layer for cross-session history and best-score tracking

### Simulation & Utility Tools
- Built a PC app for exam training, with custom timers, multi-mode state tracking, and answer mapping
- Created a commercial-use glass measurement app (Android) used in high-profile projects like Salesforce Tower

## Work Experience

### Mikey D Games — Unity Developer (VR & PC)
*Mar 2017 – Present · Remote*

Sole developer for multiple commercial games and prototypes using Unity and C#. Designed systems, gameplay mechanics, AI, UI, and deployment pipelines across immersive VR experiences and PC simulation prototypes, taking projects from concept to shipped builds end-to-end.

### Genomic Health — Robotic Process Automation Intern
*Jan 2008 – Dec 2009 · San Mateo, CA*

- Developed Tecan robot scripts in EVOware for high-precision laboratory workflows, improving efficiency and accuracy in sample processing
- Conducted QA testing and troubleshooting to ensure operational consistency, reducing workflow errors and increasing reliability

## Certifications

- Unity C# Developer Course — Udemy, Aug 2017
- Advanced Unity Scripting — Udemy, Oct 2017

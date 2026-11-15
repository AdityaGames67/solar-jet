# ✈️ Solar Jet — 3D Space Flight & Solar System Combat

An immersive, high-fidelity 3D WebGL interactive simulation of the **Solar System**, featuring photorealistic procedural canvas textures for all major planetary bodies, orbital mechanics, an instanced asteroid belt, planetary moons, and a pilotable **Sukhoi Su-35 Flanker-E** heavy air superiority space combat simulator.

---

## 🚀 How to Run

Simply launch either file:
- **`Launch_Game.bat`** (1-click Chrome launcher), or
- Open **[`index.html`](file:///D:/Aditya/index.html)** in any modern browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Brave), or
- Open the mirrored workspace copy **[`Code\index.html`](file:///D:/Aditya/Code/index.html)**

> **100% Offline Capable**: Runs completely locally using bundled Three.js libraries with procedural canvas textures—no web server, Node.js, Python, or external internet connection required.

---

## 🪐 The Solar System

| Body | Type | Orbit Radius | Moons / Features |
| :--- | :--- | :--- | :--- |
| **The Sun (Sol)** | Class G2V Star | Core (0 AU) | Turbulent solar granulation, coronal plasma, prominence ring |
| **Mercury** | Terrestrial | 38 AU | Heavily cratered silicate regolith, volcanic basins |
| **Venus** | Terrestrial | 58 AU | Shrouded in dense sulfuric acid clouds & runaway greenhouse |
| **Earth** | Terrestrial (Habitable) | 82 AU | Azure oceans, continents, dynamic cloud layer & **The Moon (Luna)** |
| **Mars** | Terrestrial | 112 AU | Rusty iron-oxide deserts, Olympus Mons, **Phobos & Deimos** |
| **Main Asteroid Belt** | Asteroids | 132 AU | 450 tumbling instanced asteroids between Mars and Jupiter |
| **Jupiter** | Gas Giant (Jovian) | 154 AU | Banded ammonia clouds, Great Red Spot, **Io, Europa, Ganymede** |
| **Saturn** | Ringed Gas Giant | 198 AU | Golden banded atmosphere, **Cassini Division rings**, **Titan** |

---

## ✈️ Sukhoi Su-35 Flanker-E Flight Simulator

The simulation features a high-fidelity flight model based on real military aerodynamics:

### Aerodynamics & Physics
- **True Velocity Inertia**: Calculates an independent momentum vector `jetVelocity` with realistic aerodynamic tracking and sideslip.
- **Physical Control Surfaces & 3D Thrust Vectoring**:
  - **Twin Tailerons**: Pitch (<kbd>R</kbd>/<kbd>F</kbd>) and differential roll (<kbd>Q</kbd>/<kbd>E</kbd>).
  - **Twin Vertical Rudders**: Yaw left and right with coordinated aerodynamic banking (<kbd>A</kbd>/<kbd>D</kbd>).
  - **Saturn AL-41F1S 3D TVC Nozzles**: Engines physically pitch and yaw with stick inputs.
- **Transonic Shockwave & Sonic Boom**: Crossing Mach 1.0 generates a 3D **Prandtl-Glauert Singularity condensation shock cone** with supersonic double-crack audio.
- **Wingtip Vapor Vortices**: Condensation streamers dynamically form under high-G turns (>3.0 G) and during afterburner boost.
- **Pugachev's Cobra Maneuver**: Press <kbd>C</kbd> to pitch up rapidly to 110° Angle of Attack (AoA), decelerating rapidly to shake pursuing hostiles.
- **Camera Views**: Press <kbd>V</kbd> to toggle between 1st-Person Cockpit View and 3rd-Person Chase Cam.

### Cockpit Audio & Rita Tactical Voice
- **Saturn AL-41F1S Turbofan Roar**: Spools smoothly from idle to afterburner thrust.
- **Transonic Wind Rush**: Bandpass-filtered air rush scaling with airspeed.
- **"Rita" Tactical Voice System**: Synthesized speech warnings ("Target locked", "Missile away", "Warning, pull up", "Maximum thrust", "Hostile destroyed", "Cobra maneuver").

---

## 🎯 Weapons & Alien Raider Combat

Deep-space hostile biomechanical raiders patrol the sector. Engage and eliminate them with the Su-35 weapons suite:

| Weapon | Control | Impact & Behavior |
| :--- | :--- | :--- |
| **30mm GSh-30-1 Autocannon** | <kbd>Space</kbd> / Left-Click | High-velocity tracer shells (35 DMG — 3 hits vaporize a raider) |
| **R-73 Archer Homing Missile** | <kbd>X</kbd> / Right-Click | Heat-seeking missile that tracks and vaporizes targets (**100 DMG 1-hit kill**) |
| **OLS-35 Optical Radar Lock** | Auto | Projects dynamic targeting reticle `[ ◆ ]` with distance and health telemetry |

---

## ⌨️ Controls Quick Reference

### Space Flight Mode (<kbd>P</kbd> to Toggle)
| Key | Action |
| :--- | :--- |
| <kbd>W</kbd> / <kbd>S</kbd> | Throttle Up / Airbrakes |
| <kbd>A</kbd> / <kbd>D</kbd> | Turn Left / Right (Yaw & Aerodynamic Bank) |
| <kbd>R</kbd> / <kbd>F</kbd> | Pitch Up / Down |
| <kbd>Q</kbd> / <kbd>E</kbd> | Roll Left / Right |
| <kbd>Shift</kbd> | Afterburner Boost |
| <kbd>C</kbd> | **Pugachev's Cobra** (110° AoA) |
| <kbd>V</kbd> | **Toggle Camera** (Cockpit / Chase) |
| <kbd>Space</kbd> / Left-Click | Fire 30mm Cannon |
| <kbd>X</kbd> / Right-Click | Launch R-73 Homing Missile |

### Solar System Orbital Mode
| Key | Action |
| :--- | :--- |
| <kbd>1</kbd> | Focus on The Sun (Sol) |
| <kbd>2</kbd> | Focus on Mercury |
| <kbd>3</kbd> | Focus on Venus |
| <kbd>4</kbd> | Focus on Earth & Moon |
| <kbd>5</kbd> | Focus on Mars |
| <kbd>6</kbd> | Focus on Jupiter |
| <kbd>7</kbd> | Focus on Saturn |
| <kbd>Esc</kbd> | Overview / Full Solar System View |
| <kbd>Space</kbd> | Toggle Orbital Auto-Rotation |
| <kbd>M</kbd> | Toggle Ambient Audio & Soundscapes |

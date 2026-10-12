# GRAVITAS — Cosmic Sandbox

**"Play God. Wreck Worlds. Watch the Beauty."**

Gravitas is a minimalist yet stunning gravity physics sandbox designed for wonder and relaxation. Built as a high-performance standalone web experience, it allows you to create solar systems, observe gravitational dances, test relativistic forces, and explore the reach of cosmic physics with intuitive controls.

![Gravitas Gameplay](file:///Users/apple/.gemini/antigravity/brain/ef1dd5bd-5d99-4b69-923c-8c0f59e0d78b/nebula_background_zoom_out_1773681789945.png)

## 🚀 Features

- **Single-File Portability**: The entire experience (HTML5, CSS3, JS, Web Audio) is self-contained in a single, highly-optimized `index.html` file with zero build dependencies.
- **Procedural Cosmic Audio (Web Audio API)**:
  - Generative binaural ambient drone that dynamically adapts to universe composition.
  - Sub-bass resonance for Black Holes.
  - Harmonized pitch-shifted release tones for body launches.
  - Deep seismic cosmic boom effects during planetary mergers.
- **Advanced Orbital Mechanics & Physics**:
  - **Predictive Trajectory Arc**: Real-time forward-simulation arc while aiming, displaying exact orbital flight paths and collision warning markers.
  - **Keplerian Orbit Assist**: Hold `Shift` (or toggle `O`) to automatically compute and lock onto the exact circular orbital velocity around the nearest host star.
  - **Roche Limit & Tidal Disruption**: Small bodies passing too close to massive stars or voids are shredded into glowing planetary debris rings.
  - **Repulsive Anti-Gravity**: White Holes exert true negative gravitational force to disperse clusters.
  - **Anchored Star System**: Pin any star in space with infinite inertia (`Alt` key or Anchor tool) for unshakeable orbital anchors.
- **Rich Celestial Body Archetypes**:
  - **Star**: Radiant core with solar flares and coronal prominences.
  - **Planet**: Dynamic 3D spherical shading with day/night terminators facing the host star.
  - **Asteroid**: High-speed cosmic debris.
  - **Void (Black Hole)**: Swirling relativistic accretion disk and photon sphere.
  - **Pulsar / Neutron Star**: Extreme density with rotating dual relativistic radiation beams sweeping the cosmos.
  - **Comet**: Icy core with solar-wind ion tails streaming away from the closest star.
  - **White Hole**: Exotic matter repelling celestial objects.
- **Famous Orbital Presets**:
  - **Solar System**: Sun with concentric planetary orbits and hierarchical Earth-Moon system.
  - **Binary Stars**: Two co-orbiting stars with a distant circumbinary planet.
  - **Figure-8 Orbit**: Chenciner-Montgomery 3-body choreography.
  - **Galaxy Crash**: Two disk galaxies colliding to form dramatic tidal bridges.
  - **Lagrange Points**: Sun-Jupiter system with Trojan asteroids in stable 1:1 resonance at $L_4$ and $L_5$.
  - **Accretion Disk**: Swarm of 55 asteroids in a rotating disk feeding a central Void.
  - **Chaos**: High-entropy multi-body gravitational turbulence.
- **Interactive Body Inspector**:
  - Click on any celestial object to view real-time velocity, mass, and radius.
  - One-click buttons to Track, Anchor, or Delete individual bodies.
- **Cosmic State & Link Sharing**:
  - Save and restore systems locally (`localStorage`).
  - Generate shareable URLs with system state embedded in the hash link (`#system=...`).
- **Science / Diagnostic Mode**:
  - Real-time toggleable velocity vectors (cyan) and gravitational force vectors (amber).

## 🛠️ Technology Stack

- **Graphics**: High-DPI HTML5 Canvas API (optimized for 60FPS).
- **Physics**: Custom Sub-stepping $N$-Body Gravitational Integrator.
- **Audio**: Web Audio API (procedural synthesis, 0 external audio files).
- **Styling**: Vanilla CSS3 with Glassmorphism (`backdrop-filter`) and CSS variables.
- **Typography**: Google Fonts (Outfit, Syncopate).

## 🎮 How to Play

1. **Open** `index.html` in any modern web browser.
2. **Launch**: Click and drag anywhere to aim and launch a celestial body.
   - *Pro Tip*: Hold **Shift** while aiming to automatically lock onto a circular orbit!
3. **Explore**:
   - **Right Click / Two-Finger Drag**: Pan the camera.
   - **Scroll / Pinch**: Zoom in/out.
   - **Presets**: Select from the top-left menu to explore famous astrophysical scenarios.
4. **Inspect**: Click directly on any body to inspect its speed, track it, or vaporize it.

## 🌌 Keyboard Shortcuts

- `Space`: Pause / Resume Simulation
- `1 - 7`: Select Celestial Body (1: Star, 2: Planet, 3: Asteroid, 4: Void, 5: Pulsar, 6: Comet, 7: White Hole)
- `Shift` / `O`: Toggle Keplerian Orbit Assist
- `M`: Toggle Cosmic Audio (Mute / Unmute)
- `S`: Toggle Science Mode (Velocity & Force Vectors)
- `F`: Toggle Focus Tracking (on primary body)
- `V`: Toggle Cinematic Mode (hide UI)
- `Z`: Undo Last Placed Body
- `R`: Reset / Center Camera
- `T`: Cycle Trail Length (Off / Medium / Long)
- `C`: Clear Universe
- `H` or `?`: Open Cosmic Guide & Shortcuts Modal
- `Esc`: Close Modals & Inspector

---

*Designed for cosmic curiosity and moments of wonder.*
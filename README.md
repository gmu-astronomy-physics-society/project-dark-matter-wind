# ☀️ Project: Hunting the Dark Matter Wind (`project-dark-matter-wind`)
> Searching for solar WIMP annihilation signatures using the IceCube Neutrino Observatory public data releases.  
> Part of the **GMAPS Collaborative Research** stream (`gmu-astronomy-physics-society`).

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/gmu-astronomy-physics-society/project-dark-matter-wind?quickstart=1)
[![Discord](https://img.shields.io/badge/Discord-#active--projects-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/KvQBnc2Gj)

---

## 🎯 The Science & Physical Lore

As the Solar System moves through the galactic dark matter halo at $\approx 220\text{ km/s}$, Earth and the Sun experience a continuous "wind" of Weakly Interacting Massive Particles (WIMPs, $\chi$). 

1. **Gravitational Capture:** WIMPs passing through the Sun can scatter elastically off solar protons and helium nuclei, losing kinetic energy until their velocities drop below solar escape velocity ($v < v_{\text{esc}}$).
2. **Core Sinking & Thermalization:** Over millions of years, captured WIMPs sink into the Sun's dense core via repeated collisions.
3. **Annihilation Signal:** Once the core density is sufficiently high, WIMPs self-annihilate:
   $$\chi + \chi \to b\bar{b}, \; \tau^+\tau^-, \; W^+W^-$$
   The decay chains produce high-energy neutrinos ($\nu_\mu, \bar{\nu}_\mu$). Unlike photons, which take over $10^4$ years to diffuse through the solar radiative zone, high-energy neutrinos escape the Sun along straight-line trajectories at light speed.

If the Sun acts as an active dark matter sink, IceCube should observe a **directional excess of high-energy muon neutrino tracks pointing toward the Sun** compared to off-source background sky directions.

---

## 🚀 Quickstart

1. Launch this environment by clicking **Open in GitHub Codespaces** above.
2. In the integrated terminal, test the sample solar transformation pipeline:
   ```bash
   python -m src.coords

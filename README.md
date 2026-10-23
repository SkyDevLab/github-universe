# 🌌 GitHub Universe 3D

An interactive 3D WebGL solar system visualization of GitHub profiles, repositories, merged pull requests, and issues. Built with **Three.js**, **Tailwind CSS**, and the **GitHub REST API**.

🚀 **Live Demo:** [https://skydevlab.github.io/github-universe/](https://skydevlab.github.io/github-universe/)

---

## ✨ Features

- 🪐 **Multi-Solar System Architecture**: Repositories are organized into realistic star systems of 7–9 planets each with 3D galactic vertical elevations ($Y \in [-130, +140]$) and orbital inclinations.
- 🌟 **Star-Scaled Planet Hierarchy**: Logarithmic star scaling dynamically sizes each planet based on its real stargazers count (from compact terrestrial worlds up to colossal Jovian gas giants).
- 🛰️ **3D Mechanical Micro-Satellites**: Merged pull requests orbit planets as detailed 3D satellites equipped with gold foil chassis, dual photovoltaic solar panels, communication dishes, and pulsing navigation LEDs.
- ☄️ **Inbound Fiery Asteroids**: Open issues drift slowly toward planets as craggy 3D tumbling rocks with dynamic friction plasma flame tails, vaporizing into incandescent spark bursts upon atmospheric re-entry.
- ☀️ **Living Central Suns**: Each star system features a glowing central fusion star with convective surface cells, pulsing coronal prominence arcs, and dynamic solar point lighting.
- 🌌 **Volumetric Deep-Space Nebulae**: Drifting galactic dust clouds (Orion Violet, Carina Magenta, Celestial Cyan, Amber Stardust) add rich cosmic depth.
- ⏱️ **4-Speed Cinematic Time Warp**: Seamlessly cycle between **Normal (1.0x)**, **Fast (2.8x)**, **Slow (0.3x)**, and **Ultra-Slow (0.06x)** for microscopic satellite inspection.
- 📡 **Live Multi-User Exploration**: Search and visualize any GitHub user in real time.

---

## 🛠️ Built With

- [Three.js](https://threejs.org/) (r128) - 3D WebGL graphics and procedural rendering
- [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls) - Free-pan galactic navigation & target tracking
- [Tailwind CSS](https://tailwindcss.com/) - Modern glassmorphic interface
- [FontAwesome 6](https://fontawesome.com/) - Sci-fi iconography
- [GitHub REST API](https://docs.github.com/en/rest) - Live repository, commit, PR, and star telemetry

---

## 🚀 Running Locally

No build tools or Node package installations are required! Simply clone and open `index.html`:

```bash
git clone https://github.com/SkyDevLab/github-universe.git
cd github-universe
# Open in your browser:
start index.html
```

---

## 🔑 GitHub API Token (Optional)

By default, the unauthenticated GitHub API rate limit is 60 requests/hour. To unlock 5,000 requests/hour for large profiles:
1. Click the **API Token** key icon in the top header.
2. Enter a personal access token (stored securely in your browser's `localStorage`).

---

## 📄 License

MIT License © 2026 [SkyDevLab](https://github.com/SkyDevLab)

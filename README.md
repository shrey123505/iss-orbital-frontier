# 🛰️ ISS Orbital Frontier - 3D Models & Assets Repository

Welcome to **ISS Orbital Frontier** repository. This repository stores all high-quality 3D assets (`.glb` files) required for the International Space Station simulation, web games, and AI Studio prototypes.

---

## 📁 Repository Structure

```
iss-orbital-frontier/
│
├── public/
│   └── models/
│       ├── iss/
│       │   ├── iss-exterior.glb
│       │   └── iss-interior.glb
│       │
│       ├── astronaut/
│       │   └── astronaut.glb
│       │
│       └── planets/
│           ├── earth.glb
│           ├── sun.glb
│           ├── moon.glb
│           ├── mercury.glb
│           ├── venus.glb
│           ├── mars.glb
│           ├── jupiter.glb
│           ├── saturn.glb
│           ├── uranus.glb
│           ├── neptune.glb
│           └── pluto.glb
│
├── ASSET_CREDITS.md
├── package.json
└── README.md
```

---

## 🌐 Direct Asset URLs (For AI Studio, Three.js & Web)

You can load these models directly into your 3D engines (Three.js, Babylon.js, React Three Fiber, Model Viewer) using either **jsDelivr CDN** (recommended for speed and automatic CORS headers) or **GitHub Raw**:

### 🛰️ Space Station & Astronaut
| Asset | jsDelivr CDN URL | GitHub Raw URL |
|---|---|---|
| **ISS Exterior** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/iss/iss-exterior.glb` | `https://raw.githubusercontent.com/shrey123505/iss-orbital-frontier/main/public/models/iss/iss-exterior.glb` |
| **ISS Interior (162 MiB - Git LFS)** | `https://media.githubusercontent.com/media/shrey123505/iss-orbital-frontier/main/public/models/iss/iss-interior.glb` | `https://media.githubusercontent.com/media/shrey123505/iss-orbital-frontier/main/public/models/iss/iss-interior.glb` |
| **Astronaut** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/astronaut/astronaut.glb` | `https://raw.githubusercontent.com/shrey123505/iss-orbital-frontier/main/public/models/astronaut/astronaut.glb` |

> ℹ️ **Note on ISS Interior (Git LFS):** Since `iss-interior.glb` is 162 MiB, it is tracked via Git LFS. Always use `media.githubusercontent.com` (which serves the full 162 MiB real binary with CORS headers `Access-Control-Allow-Origin: *`) rather than `raw.githubusercontent.com` (which only returns the 134-byte LFS pointer).

### 🪐 Planets & Solar System
| Planet | jsDelivr CDN URL |
|---|---|
| **Sun** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/sun.glb` |
| **Mercury** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/mercury.glb` |
| **Venus** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/venus.glb` |
| **Earth** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/earth.glb` |
| **Moon** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/moon.glb` |
| **Mars** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/mars.glb` |
| **Jupiter** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/jupiter.glb` |
| **Saturn** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/saturn.glb` |
| **Uranus** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/uranus.glb` |
| **Neptune** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/neptune.glb` |
| **Pluto** | `https://cdn.jsdelivr.net/gh/shrey123505/iss-orbital-frontier@main/public/models/planets/pluto.glb` |

---

## 📜 Asset Credits & Attribution

All models are open-source and released under Creative Commons licenses (CC-BY-4.0 / CC-BY-SA-4.0). Please see [ASSET_CREDITS.md](./ASSET_CREDITS.md) for full attribution links and details.

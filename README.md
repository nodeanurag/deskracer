# 🏎️ Desk Racer

A miniature 1:87 scale coaster time-trial racing game set across a cozy golden-hour desk diorama.

> **Created with Gemini 4 Carbon**

---

## ✨ Features

- **Miniature 1:87 Micro Kart:** High-speed physics-driven time-trial coaster racing across desk props, books, and coiled tracks.
- **Rapier3D Physics Engine:** 60 FPS real-time vehicle simulation, bank turns, track gravity, and collision responses using `@dimforge/rapier3d-compat`.
- **Three.js Visuals:** Cinematic lighting with ACES Filmic tone mapping, Unreal Bloom, ambient occlusion, and dynamic camera angles.
- **Procedural Web Audio Engine:** Reactive spatial audio synthesizers for real-time engine revs, tire squeals, curb rumbles, and drifts without audio latency.
- **Multiple Camera Modes:** 8 camera angles including Cockpit Visor POV, Chase Cam, Drone / Helicopter, Course Pan, and Diorama modes.
- **Vercel Analytics:** Pre-integrated with `@vercel/analytics` for performance and visitor insights.

---

## 🎮 Controls

| Action | Keyboard | Touch / Mobile |
| :--- | :--- | :--- |
| **Accelerate** | `W` / `↑` | On-screen Accel pedal |
| **Brake / Reverse** | `S` / `↓` | On-screen Brake pedal |
| **Steer Left / Right** | `A` / `D` or `←` / `→` | Touch steering arrows |
| **Respawn / Reset** | `R` | Reset button |
| **Switch Camera** | Keys `1` – `8` | Camera menu button |
| **Mute / Unmute** | `M` | Top-right sound toggle |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer)
- npm, pnpm, or yarn

### 1. Clone & Install Dependencies

```bash
git clone https://github.com/nodeanurag/deskracer.git
cd deskracer
npm install
```

### 2. Start Local Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to play the game!

### 3. Production Build

```bash
npm run build
```

---

## 🌐 Deploy to Vercel

This repository includes a [`vercel.json`](vercel.json) configuration with edge rewrites for 3D model assets and pre-integrated Vercel Analytics:

1. Push your repository to GitHub.
2. Import the project into [Vercel](https://vercel.com/new).
3. Vercel automatically detects the Vite configuration and builds the project (`npm run build` -> `dist/`).
4. Enable **Web Analytics** in your Vercel project dashboard to view live player metrics.

---

## 🛠️ Built With

- **[Three.js](https://threejs.org/)** – 3D rendering and post-processing
- **[Rapier 3D](https://rapier.rs/)** – Fast WebAssembly physics simulation
- **[Vite](https://vitejs.dev/)** – Next-generation frontend build tool
- **[Vercel Analytics](https://vercel.com/analytics)** – Privacy-first web analytics

# 🗿 Niraniya Heritage — Cinematic Heritage Carvings Web Application

[![React 19](https://img.shields.io/badge/React-19-61DAFB?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite)](https://vitejs.dev/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-12-EA4C89?logo=framer)](https://www.framer.com/motion/)
[![React Router 7](https://img.shields.io/badge/React_Router-7-CA4245?logo=react-router)](https://reactrouter.com/)

> A cinematic, interactive web experience showcasing the timeless hand-carved stonework of **Niraniya Heritage**. Featuring custom cursor physics, fire-ash particle simulations, immersive smooth routing, and museum-grade visual showcases.

---

## ✨ Features

- **🔥 Fire & Ash Particle Canvas**: Dynamic visual particle effects simulating the sacred temple atmosphere.
- **✨ Custom Premium Cursor**: Reactive physics-based custom cursor following user interactions.
- **🎬 Cinematic Smooth Navigation**: Page transitions and section jumps orchestrated with Framer Motion and React Router 7.
- **🏛️ Product Showcases**: High-definition presentations of Granite Shiva, Marble Buddha, Obsidian Ganesha, and Sandstone Carvings.
- **📱 Fully Responsive**: Flawlessly adapts to ultra-wide desktop monitors, tablets, and smartphones.

---

## 🏗️ Architecture

```mermaid
graph TD
    App[App.jsx / Router Context] --> Preloader[Cinematic Preloader]
    App --> Cursor[Premium Physics Cursor]
    App --> Particles[FireAsh Particle Canvas]
    App --> Nav[Navigation Header]
    App --> Pages[Page Router]
    
    Pages --> Home[Home Showcase]
    Pages --> Showcase[Artifact Explorer]
    Pages --> Gallery[Artisan Gallery]
    Pages --> Enquiry[Client Enquiry Portal]
```

---

## 🛠️ Tech Stack

- **Framework**: React 19
- **Build Tool**: Vite 8
- **Animations**: Framer Motion 12
- **Routing**: React Router 7 (`react-router-dom`, `react-router-hash-link`)
- **Icons**: Lucide React

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Harshxu/niraniyaheritageantigravity.git
cd niraniyaheritageantigravity

# Install dependencies
npm install

# Start development server
npm run dev
```

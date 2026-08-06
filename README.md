# 🚀 GLM-Launcher-Minecraft-On-Web

A **mobile-focused web launcher** designed to run modified Eaglercraft directly in your browser with touch-first controls, built-in mods, shaders, resource packs, and custom settings (PC is fully supported too!). 

It delivers massive performance gains, and an unreleased version is dropping soon featuring a **successful port of Vulkan (via WebGPU)** to push browser rendering even further.

This project provides a customizable launcher layer for Eaglercraft — I do not claim ownership of the underlying engine. It is aggressively optimized and includes custom additions detailed below ⚙️

---

## 👋 Welcome

Start by reading our **Credits** below — it's important to credit everyone involved in the Eaglercraft project. Then check out what this launcher actually does, and why you should choose us! 💚

---

## ✨ Why GLM-Launcher?

- 📱 **Mobile-First Design** — Tailored experience with HUD controls for mobile that actually work well (credit to the original creator!), while maintaining full PC compatibility.

- 🌋 **Vulkan (WebGPU) Support Coming Soon** — Successfully ported Vulkan via WebGPU in an unreleased build that will be released shortly for next-level browser graphics performance.

- 🔄 **Frequent updates** — Active development with continuous feature drops.

- 📴 **Fully offline** — Run Eaglercraft with no internet required after the initial load.

- ⚡ **Performance-first** — Engine optimizations take priority over UI fluff, backed by regular performance patches.

- 🎛️ **Deep customization** — Allocate RAM and switch renderer modes on the fly.

- 🎨 **Shader support** — Built-in presets (No Shaders, Basic, Full, Performance), or upload your own custom shader packs (`.zip`).

- 🖼️ **Resource pack support** — Upload and apply your own custom resource packs (`.zip`).

- 🗂️ **No localhost required** — Single `.html` file, just install and launch.

- 🐢➡️🐇 **Optimized for low-end hardware** — Scales smoothly down to weak mobile chips and decade-old laptops without dedicated GPUs.

- 🧩 **Mod support** — Load provided `.js` mods or craft your own!

---

## ⚡ Performance

Benchmarked on a phone that doesnt support most of the opengl stuff:

- 🎯 49–60 FPS with shaders enabled

- 🧱 Zero FPS drop during chunk loading

- 🛠️ Fully optimized rendering pipeline, including custom rewrites to Eaglercraft's core rendering system

---

## 🙌 Credits

### Original Eaglercraft

**lax1dude:**

- Creator of Eaglercraft

- Ported Minecraft 1.8 source to TeaVM

- Core optimization, platform abstraction layer, OpenGL emulator

- Shader pack, PBR resource pack, mobile/touch support

- Multiplayer backends, shared world relay server, patch/build system

**ayunami2000:**

- Bug fixes, WebRTC shared worlds & voice chat

- Touch support, Velocity plugin support

- Resource packs, screen recording, seamless fullscreen

### GLM-Craft (this project) 🛠️

- 🌋 Vulkan GPU support (for mobile only most likely) (WebGPU) engine port (unreleased / releasing soon)

- 🧩 Mod support system (new — not in original Eaglercraft)

- 🎨 Shader support (built-in presets + custom shader pack uploads)

- 🖼️ Resource pack support (custom resource pack uploads)

- 🎛️ Custom render options

- 💾 RAM allocation controls

- 👤 Rebuilt skin/username selector

- ⚡ Performance optimizations, including partial rewrites of the rendering system, draw call batching, texture/mipmap tuning, frustum culling, and post-processing improvements

---

## 📸 Screenshots

<img width="1280" height="768" alt="GLM Launcher Home" src="https://github.com/user-attachments/assets/5a559ca6-5a64-448e-9f00-346a7bf32f9f" />

<img width="1280" height="768" alt="GLM Launcher Gameplay" src="https://github.com/user-attachments/assets/f5067d0e-7d02-4caa-9a7f-c459d89eea43" />

---

⭐ If you like this project, consider starring the repo!

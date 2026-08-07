# 🚀 GLM-Launcher-Minecraft-On-Web

A **mobile-focused web launcher** designed to run modified Eaglercraft directly in your browser with touch-first controls, built-in mods, shaders, resource packs, and custom settings (PC is fully supported too!). 

It delivers massive performance gains powered by a **WebGPU translation layer** — giving mobile devices native **Vulkan** execution, PC users **Direct3D 12 (DX12)** support, and significantly higher FPS and stability overall.

This project provides a customizable launcher layer for Eaglercraft — I do not claim ownership of the underlying engine. It is aggressively optimized and includes custom additions detailed below ⚙️

---

## 👋 Welcome

Start by reading our **Credits** below — it's important to credit everyone involved in the Eaglercraft project. Then check out what this launcher actually does, and why you should choose us! 💚

---

## ✨ Why GLM-Launcher?

- 📱 **Mobile-First Design** — Tailored experience with HUD controls for mobile that actually work well (credit to the original creator!), while maintaining full PC compatibility.

- 🌐 **WebGPU Translation Layer** — Built-in WebGPU support that routes to native **Vulkan on mobile** and **Direct3D 12 (DX12) on PC** for maximum graphics pipeline efficiency.

- 🛠️ **TeaVM Code Optimizations** — Core Eaglercraft obfuscated source code has been refactored and tuned directly for smoother JS execution on mobile web engines.

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

Benchmarked on a mobile device with limited native OpenGL support:

- 🎯 49–60 FPS with shaders enabled

- 🧱 Zero FPS drop during chunk loading

- 🛠️ Fully optimized rendering pipeline, including custom rewrites to Eaglercraft's core rendering system and TeaVM source tuning

Benchmarked on a mobile device after WebGPU support (Using vulkan on WebGPU)

- 🎯 60FPS Locked, No stutters or lag

- 🧱 Zero FPS drop during chunk loading

- 🛠️ Fully optimized rendering pipeline, including custom rewrites to Eaglercraft's core rendering system and TeaVM source tuning and WebGPU implementation!

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

- 🌐 WebGPU translation layer (Vulkan on Mobile / DX12 on PC)

- ⚡ TeaVM obfuscated source code refactoring & mobile optimizations

- 🧩 Mod support system (new — not in original Eaglercraft)

- 🎨 Shader support (built-in presets + custom shader pack uploads)

- 🖼️ Resource pack support (custom resource pack uploads)

- 🎛️ Custom render options

- 💾 RAM allocation controls

- 👤 Rebuilt skin/username selector

- ⚡ Performance optimizations, including partial rewrites of the rendering system, draw call batching, texture/mipmap tuning, frustum culling, and post-processing improvements

---

## 📸 Screenshots

- Picture of the launcher *(Note: Launcher design changes frequently and may vary slightly from below)*

<img width="1280" height="768" alt="preview (6)" src="https://github.com/user-attachments/assets/4892525c-c613-464c-b141-489f35aac384" />

<img width="1280" height="768" alt="preview (7)" src="https://github.com/user-attachments/assets/7d8c0dec-4be4-4bed-9afc-e511d166d9ba" />

-pictures of mods being used (includes keyboard thing,minimap,custom sky colour. sky colour is extremly performance taking

<img width="1280" height="650" alt="preview (8)" src="https://github.com/user-attachments/assets/88244edb-5138-4ec5-934b-ef4ed7199a6f" />



- Picture of a PC test *(Old PC with weak CPU & no dedicated GPU — achieving a stable 40–50 FPS via rendering optimizations old version as well)*

<img width="1280" height="768" alt="GLM Launcher Gameplay" src="https://github.com/user-attachments/assets/f5067d0e-7d02-4caa-9a7f-c459d89eea43" />

---

⭐ If you like this project, consider starring the repo!

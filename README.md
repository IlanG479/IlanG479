# Hi, I'm Ilan

<img src="assets/boot.svg" width="840" alt="Terminal boot log: lilota, vibecraft, claude-os, ratio" />

I mostly write systems code — embedded C on microcontrollers, Rust renderers — and build tools for things I actually use.

<!-- Add a line or two here in your own words: who you are, where you're at. -->

## Now building

```console
$ ilan --now
▸ lilota      ULP coprocessor work — wake-on-Nth-press, deep-sleep loop retention
▸ claude-os   read-only operator console for a multi-tool AI stack
▸ next        <!-- fill this in when it changes -->
```

## Build log

<!-- Newest first. Add an entry each time you ship something. -->

### 2026

<details>
<summary><b>Aug</b> — <b>Claude OS</b> · one-page operator console for an AI tool stack</summary>

<br>

Reads what's already on disk — Claude Code, Codex, OpenRouter, Pinecone, Obsidian — and renders one scrollable dashboard: subscriptions, token spend, skills ROI, a 3D memory graph, and a daily prescription engine that names the four highest-impact things to fix. Read-only by design; it never writes to a source tool's data directory.

**New to me here:** three.js force graphs, and designing something whose entire value is that it *doesn't* mutate the data it reads.

`React` · `TypeScript` · `Vite` · `three.js`

</details>

<details>
<summary><b>Aug</b> — <b>Ratio</b> · local-first Chrome side panel for Instagram review</summary>

<br>

Loads followers and following in parallel, verifies the signed-in account matches the one requested, and walks you through non-followers one at a time. Every decision is stored locally against stable Instagram account IDs — no password, no relationship data, no server.

**New to me here:** Chrome's side panel API, and building a keyboard-first review loop (number keys, undo, deferred queue) that stays fast over hundreds of accounts.

`TypeScript` · `Chrome Extensions`

→ [ratio-instagram-follower-filter](https://github.com/IlanG479/ratio-instagram-follower-filter)

</details>

<details>
<summary><b>Jul–Aug</b> — <b>Lilota</b> · embedded runtime research @ Stony Brook COMPAS Lab</summary>

<br>

Lilota — *Little Interpreted Language Over The Air* — is a Tcl-like interpreter for microcontrollers, so a device stays inspectable and scriptable after it's flashed. Low-level mechanisms in C, device policy in Lil/Tcl scripts.

26 commits, concentrated in the ESP32 ULP coprocessor layer: waking from deep sleep after N debounced button presses, retaining deep-sleep loops across wake, and restructuring the RTC clock into `rtctime` / `tzset` subcommands so time survives a power-down. Some work also landed on the RP2040 and ESP8266 ports.

**New to me here:** writing for a coprocessor that runs while the main CPU is asleep — a context where you get a few hundred bytes and no allocator.

`C` · `ESP-IDF` · `ESP32 ULP` · `RP2040`

</details>

<details>
<summary><b>Jul</b> — <b>Vibecraft</b> · native Rust voxel engine (CSIRE side project)</summary>

<br>

A Minecraft-like engine written from scratch in Rust against a `wgpu` renderer — procedural terrain, lighting, block interaction, inventory, survival values, native persistence, commands, and audio. Targets Java Edition 1.21.1 gameplay and assets without being protocol- or NBT-compatible.

Built alongside [@bobz5460](https://github.com/bobz5460) and [@dac63701](https://github.com/dac63701) during CSIRE.

<!-- Describe your own role here in one line — I don't want to guess at it. -->

`Rust` · `wgpu` · `winit` · `nalgebra`

→ [bobz5460/vibecraft](https://github.com/bobz5460/vibecraft)

</details>

### 2025

<details>
<summary><b>Rove</b> · flight search & synthetic routing (HUVTSP team project)</summary>

<br>

A FastAPI service over the Amadeus API doing route optimization with intelligent layover selection, plus a redemption-value calculator comparing flights, hotels, and gift cards. Direct, 1-stop, and 2-stop synthetic route generation.

<!-- Add the higher-level work you did on this recently. -->

`Python` · `FastAPI` · `Amadeus API`

MIT · © 2025 Dominik · built by the Rove Development Team

</details>

## Stack

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-283593?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi Pico](https://img.shields.io/badge/RP2040-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![wgpu](https://img.shields.io/badge/wgpu-005A9C?style=flat-square&logo=webgpu&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

## GitHub stats

<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IlanG479&layout=compact&langs_count=8&theme=github_dark&hide_border=true&count_private=true" height="160" alt="Top languages" />
  <img src="https://streak-stats.demolab.com?user=IlanG479&theme=github-dark-blue&hide_border=true" height="160" alt="Contribution streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/IlanG479/IlanG479/output/snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/IlanG479/IlanG479/output/snake.svg" alt="Contribution snake animation" width="100%" />
</picture>

## Connect

[![Email](https://img.shields.io/badge/email-0a0e14?style=flat-square&logo=gmail&logoColor=white)](mailto:ilan.gunawardena@gmail.com)

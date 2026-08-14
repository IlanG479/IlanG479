<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e14,45:1e3a8a,100:22d3ee&height=190&section=header&text=Ilan%20Gunawardena&fontSize=46&fontColor=e6edf3&fontAlignY=34&desc=building%20things%20that%20run%20close%20to%20the%20metal&descAlignY=54&descSize=15" width="100%" alt="" />

<p align="center">
  <a href="https://github.com/IlanG479">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2600&pause=700&color=22D3EE&center=true&vCenter=true&width=580&lines=Rust+renderers+%C2%B7+wgpu;Tcl+interpreters+on+ESP32;Chrome+extensions+%C2%B7+no+server;AI+operator+consoles" alt="Rust renderers, Tcl interpreters on ESP32, Chrome extensions, AI operator consoles" />
  </a>
</p>

<p align="center">
  <img src="assets/boot.svg" width="840" alt="Terminal boot log: lilota, vibecraft, claude-os, ratio" />
</p>

<img src="assets/rule.svg" width="100%" alt="" />

## `> now building`

```console
$ ilan --now
▸ lilota      ULP coprocessor work — wake-on-Nth-press, deep-sleep loop retention
▸ claude-os   read-only operator console for a multi-tool AI stack
▸ next        <!-- fill this in when it changes -->
```

<img src="assets/rule.svg" width="100%" alt="" />

## `> build log`

<!-- Newest first. Add an entry each time you ship something. -->

### 2026

<details>
<summary><b>Aug</b> — <b>Claude OS</b> · one-page operator console for an AI tool stack</summary>

<br>

Reads what's already on disk — Claude Code, Codex, OpenRouter, Pinecone, Obsidian — and renders one scrollable dashboard: subscriptions, token spend, skills ROI, a 3D memory graph, and a daily prescription engine that names the four highest-impact things to fix. Read-only by design; it never writes to a source tool's data directory.

**New to me here:** three.js force graphs, and designing something whose entire value is that it *doesn't* mutate the data it reads.

`React` `TypeScript` `Vite` `three.js` `Radix` `Cloudflare`

</details>

<details>
<summary><b>Aug</b> — <b>Ratio</b> · local-first Chrome side panel for Instagram review</summary>

<br>

Loads followers and following in parallel, verifies the signed-in account matches the one requested, and walks you through non-followers one at a time. Every decision is stored locally against stable Instagram account IDs — no password, no relationship data, no server.

**New to me here:** Chrome's side panel API, and building a keyboard-first review loop (number keys, undo, deferred queue) that stays fast over hundreds of accounts.

`TypeScript` `Chrome Extensions` `Local-first`

**→ [ratio-instagram-follower-filter](https://github.com/IlanG479/ratio-instagram-follower-filter)** · public

</details>

<details>
<summary><b>Jul–Aug</b> — <b>Lilota</b> · embedded runtime research @ Stony Brook COMPAS Lab</summary>

<br>

Lilota — *Little Interpreted Language Over The Air* — is a Tcl-like interpreter for microcontrollers, so a device stays inspectable and scriptable after it's flashed. Low-level mechanisms in C, device policy in Lil/Tcl scripts.

**26 commits**, concentrated in the ESP32 ULP coprocessor layer: waking from deep sleep after N debounced button presses, retaining deep-sleep loops across wake, and restructuring the RTC clock into `rtctime` / `tzset` subcommands so time survives a power-down. Some work also landed on the RP2040 and ESP8266 ports.

**New to me here:** writing for a coprocessor that runs while the main CPU is asleep — a context where you get a few hundred bytes and no allocator.

`C` `ESP-IDF` `ESP32 ULP` `RP2040` `Tcl`

**→ COMPAS-Lab/lilota** · private research repo

</details>

<details>
<summary><b>Jul</b> — <b>Vibecraft</b> · native Rust voxel engine (CSIRE side project)</summary>

<br>

A Minecraft-like engine written from scratch in Rust against a `wgpu` renderer — procedural terrain, lighting, block interaction, inventory, survival values, native persistence, commands, and audio. Targets Java Edition 1.21.1 gameplay and assets without being protocol- or NBT-compatible.

Built alongside [@bobz5460](https://github.com/bobz5460) and [@dac63701](https://github.com/dac63701) during CSIRE.

<!-- Describe your own role here in one line — I don't want to guess at it. -->

`Rust` `wgpu` `winit` `nalgebra` `rodio`

**→ [bobz5460/vibecraft](https://github.com/bobz5460/vibecraft)** · upstream

</details>

### 2025

<details>
<summary><b>Rove</b> · flight search & synthetic routing (HUVTSP team project)</summary>

<br>

A FastAPI service over the Amadeus API doing route optimization with intelligent layover selection, plus a redemption-value calculator comparing flights, hotels, and gift cards. Direct, 1-stop, and 2-stop synthetic route generation.

<!-- Add the higher-level work you did on this recently. -->

`Python` `FastAPI` `Amadeus API`

MIT · © 2025 Dominik · built by the Rove Development Team

</details>

<img src="assets/rule.svg" width="100%" alt="" />

## `> stack`

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>
<p>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/Raspberry%20Pi%20Pico-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="RP2040" />
  <img src="https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge&logo=webgpu&logoColor=white" alt="wgpu" />
  <img src="https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="three.js" />
</p>
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Chrome%20Extensions-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome Extensions" />
</p>

<img src="assets/rule.svg" width="100%" alt="" />

## `> activity`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=IlanG479&bg_color=0a0e14&color=e6edf3&line=22d3ee&point=3b82f6&area=true&area_color=1e3a8a&hide_border=true&custom_title=contribution%20graph" width="98%" alt="Contribution activity graph" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IlanG479&layout=compact&langs_count=8&theme=github_dark&bg_color=0a0e14&title_color=22d3ee&text_color=8b98ad&hide_border=true&count_private=true" height="165" alt="Top languages" />
  <img src="https://streak-stats.demolab.com?user=IlanG479&theme=github-dark-blue&background=0a0e14&ring=22d3ee&fire=3b82f6&currStreakLabel=22d3ee&hide_border=true" height="165" alt="Contribution streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/IlanG479/IlanG479/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/IlanG479/IlanG479/output/snake.svg" />
    <img src="https://raw.githubusercontent.com/IlanG479/IlanG479/output/snake.svg" alt="Contribution snake animation" width="98%" />
  </picture>
</p>

<img src="assets/rule.svg" width="100%" alt="" />

<!--
  A line you actually believe, from a real source, with attribution.
  Leaving it blank rather than filling it with something invented.

  > "…"
  > — Author
-->

<p align="center">
  <a href="mailto:ilan.gunawardena@gmail.com">
    <img src="https://img.shields.io/badge/email-0a0e14?style=for-the-badge&logo=gmail&logoColor=22d3ee" alt="Email" />
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,55:1e3a8a,100:0a0e14&height=120&section=footer" width="100%" alt="" />

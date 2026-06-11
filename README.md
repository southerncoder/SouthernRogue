# Rogue Collection: rogue-rs

This repository contains a data-driven reimplementation of Rogue in modern Rust, known as **rogue-rs**.

## 🚀 Overview

**Created by [SouthernCoder](https://github.com/southerncoder)** as a from-scratch reimagining of the classic Rogue, developed using **AI agentic coding** with [GitHub Copilot](https://github.com/features/copilot). This project uses the legacy C/C++ collection by Mike Kamermans as the authoritative reference for behavioral logic and rules.

Built on [`bracket-lib`](https://github.com/amethyst/bracket-lib) (terminal rendering, FOV, pathfinding), a lightweight ECS, and `serde`/RON for content management.

## ✨ Features

- **Playable**: `cd rogue-rs && cargo run --bin rogue`
- **Web/WASM**: Runs in the browser via macroquad — `cargo build -p rogue-web --target wasm32-unknown-unknown`
- **Easy to extend**: Add dungeon levels by dropping RON files in `rogue-rs/assets/levels/`. Supports both procedural and hand-authored fixed maps with no recompilation required for native.
- **Interactive UI**: Features an interactive inventory, autopilot bot, and multiple color themes (classic, amber, green, boxy, tiled).

The game engine follows the rules of **Unix Rogue v5.4.2** as its canonical reference.

See [`rogue-rs/README.md`](rogue-rs/README.md) for full documentation and [`rogue-rs/docs/`](rogue-rs/docs/) for architecture, gameplay, and authoring guides.

---

## 📜 Credits & Licenses

### Original Rogue Collection
This project was inspired by and built upon the **[Retro Rogue Collection](https://github.com/mikeyk730/Rogue-Collection)** by **Mike Kamermans (@mikeyk730)**. We are grateful for the preservation of these classic versions which served as the foundation for our reimplementation.

### rogue-rs (Rust Reimplementation)
**License**: MIT — see [`rogue-rs/`](rogue-rs/).

*Note: While we have migrated the core rules from the legacy collection, all original license information regarding Unix Rogue and its components can be found in the historical records of the Retro Rogue Collection.*

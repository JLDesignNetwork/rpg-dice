# RPG Dice Knowledge Base & Documentation Wiki

> **Project:** JLDN RPG Dice (Pulsar Extension)  
> **Generation Epoch:** `2606.2.0-s`  
> **Author:** Jeff Langdon (JL Design Network)  
> **Status:** Active Lightweight TTRPG Dice Rolling Engine  

Welcome to the official documentation and reference wiki for **RPG Dice**, a focused, lightweight inline dice rolling engine for the **Pulsar** text editor.

---

## 📚 Documentation Index

| Guide / Chapter | Description | Document |
| :--- | :--- | :--- |
| **Package Overview & Architecture** | Pulsar workspace command registration and dice parser engine. | [Architecture](architecture.md) |
| **Usage & Command Palette** | Quick start, editor keybindings, and inline evaluation. | [Usage Guide](usage.md) |
| **🎲 Dice Engine & Stat Pools** | Notation syntax (`1d20+5`), Fate/Fudge rolls, 3d6 / 4d6 stat pools. | [Dice Engine](dice_engine.md) |
| **🗺️ Strategic Roadmap** | Multi-generational roadmap and future horizons. | [Roadmap](../.dev/ROADMAP.md) |

---

## 🚀 Key Capabilities

- **Inline Regex Dice Math:** Evaluate standard dice notations (`1d20+5`, `3d6-1`, `8d8`) inline inside active editor buffers.
- **Fate / Fudge Mode:** First-class support for Fate dice (`-1`, `0`, `+1`).
- **Ability Score Generators:** Generate 3d6 and 4d6 drop-lowest attribute arrays with a single command.
- **Cryptographically Secure PRNG:** Powered by Node.js native `crypto.randomInt` to eliminate pseudo-random bias.

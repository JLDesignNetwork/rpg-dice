# RPG Dice

[![GVS](https://img.shields.io/badge/GVS-2606.2.0--s-purple?style=flat-square)](https://github.com/JLDesignNetwork/Generational-Versioning-Schema)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE.md)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/jldesignnetwork)

Welcome to **RPG Dice** (JLDN Generational Versioning Schema: `2606.2.0-s`), a focused, lightweight inline dice rolling engine and ability score pool generator for the **Pulsar** text editor.

---

## Overview

* **Author:** Jeff Langdon (JL Design Network)
* **Version:** `2606.2.0-s` (Stable Release)
* **Active Generation:** `2606`
* **Target Editor:** [Pulsar](https://pulsar-edit.dev/) (`^1.0.0`)

---

## 📚 In-Repo Documentation Wiki

- 📖 **[Knowledge Base Wiki Index](docs/index.md):** Complete package documentation.
- 🏗️ **[Package Architecture](docs/architecture.md):** Subsystem architecture and math parser engine.
- 🛠️ **[Usage & Command Guide](docs/usage.md):** Pulsar installation, keybindings, and command palette triggers.
- 🎲 **[Dice Engine & Stat Pools](docs/dice_engine.md):** Dice syntax (`1d20+5`), Fate/Fudge rolls, and 3d6/4d6 stat pool generators.
- 🗺️ **[Strategic Roadmap](.dev/ROADMAP.md):** Multi-generational roadmap.
- 📝 **[Changelog](CHANGELOG.md):** Full chronological release history.

---

## Core Capabilities

1. 🎲 **Inline Dice Evaluation:** Type or highlight dice math (`1d20+5`, `2d8-2`, `8d8`) and calculate outcomes directly in the text editor buffer.
2. 🪙 **Fate / Fudge Dice:** First-class support for Fate dice expressions (`4dF`).
3. 📊 **Ability Score Pools:** Generate 3d6 and 4d6 drop-lowest attribute arrays with a single hotkey.
4. 🔒 **Cryptographically Secure PRNG:** Powered by Node.js native `crypto.randomInt` (CWE-338 compliant).

---

## Funding & Support

If you find this Pulsar package helpful, consider supporting ongoing development:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=flat-square&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/jldesignnetwork)

---

## License & Attribution

Licensed under the [MIT License](LICENSE.md). Designed and maintained by Jeff Langdon / JL Design Network. All rights reserved.

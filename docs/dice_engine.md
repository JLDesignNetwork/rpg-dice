# 🎲 Dice Engine & Stat Pools

> **Document:** `docs/dice_engine.md`  
> **Author:** Jeff Langdon (JL Design Network)  

---

## 1. Dice Rolling Syntax

RPG Dice parses polyhedral dice expressions directly from selected text or prompt buffers:

- **Standard Dice:** `[count]d[sides] [+/- modifier]` (e.g. `1d20+5`, `2d8-2`, `4d6`).
- **Fate / Fudge Dice:** `[count]dF` (e.g. `4dF` rolling values from `-1` to `+1`).

---

## 2. Stat Pool Generation Methods

- **Method 3 (`3d6`):** Rolls 3 six-sided dice per attribute score.
- **Method 4 (`4d6 drop lowest`):** Rolls 4 six-sided dice per attribute, discarding the lowest individual die and summing the remaining three.

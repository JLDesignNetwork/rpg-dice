# JLDN RPG Dice Strategic Roadmap

> **Project:** JLDN RPG Dice (Pulsar IDE Package)  
> **Generation Epoch:** `2606` (Genesis: June 2026)  
> **Author:** Jeff Langdon (JL Design Network)  
> **Status:** Active Lightweight TTRPG Dice Rolling Engine  

---

## Strategic Vision

**RPG Dice** is a focused, lightweight inline dice rolling engine and ability score pool generator for the **Pulsar** text editor. It provides ultra-fast inline dice notation evaluation (`1d20+5`, Fate/Fudge rolls, 3d6 / 4d6 stat pool generators).

```
                      JLDN RPG DICE GENERATIONAL ROADMAP
  ┌────────────────────────┐       ┌────────────────────────┐       ┌────────────────────────┐
  │ Generation 2606        │       │ Generation 2608        │       │ Future Horizons        │
  │ Pulsar Lightweight Core│ ───>  │ Standalone CLI Runner  │ ───>  │ Math REPL & VTT Socket │
  │ Crypto-Secure Random   │       │ Advanced Math Modifiers│       │ VS Code Extension Port │
  └────────────────────────┘       └────────────────────────┘       └────────────────────────┘
```

---

## Generational Backlogs & Horizons

### Generation 2606 (Active Baseline)
- [x] **Inline Dice Evaluation:** Fast regex math parser for standard and Fate dice notations.
- [x] **Ability Score Pool Generators:** 3d6 and 4d6 drop-lowest generation methods.
- [x] **Cryptographically Secure PRNG:** Native `crypto.randomInt` engine to eliminate pseudo-random bias.
- [x] **Orange Team Legacy Modernization:** Full baseline scaffolding, CI quality gate, and CodeQL security suite.

### Generation 2608+ (Future Tooling)
- [ ] **CLI Binary (`@jldn/dice`):** Lightweight terminal dice utility for CLI workflows.
- [ ] **Complex Polyhedral Expressions:** Support for exploding dice (`1d6!`), penetrating dice, and target-number success counts.

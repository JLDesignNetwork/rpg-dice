# JLDN RPG Dice — Package Architecture

> **Document:** `docs/architecture.md`  
> **Author:** Jeff Langdon (JL Design Network)  
> **Generation:** `2606`  

---

## 1. Subsystem Architecture

RPG Dice maintains a minimalist, high-speed execution footprint:

```
                            RPG DICE TOPOLOGY
  ┌──────────────────────────────────────────────────────────────────┐
  │ lib/rpg-dice.js (Pulsar Package Entrypoint & Command Listener)  │
  │   └── lib/engine.js (Math Parsing & Crypto-Secure Random PRNG)   │
  └──────────────────────────────────────────────────────────────────┘
```

1. **`rpg-dice.js`:** Attaches to the Pulsar command registry (`rpg-dice:roll`) and text editor selections.
2. **`engine.js`:** Pure mathematical evaluator utilizing `crypto.randomInt` for deterministic, unbiased dice rolling.

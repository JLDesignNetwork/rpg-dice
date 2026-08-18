# Contributing to RPG Dice

Thank you for contributing to **RPG Dice**! Please review the guidelines below.

---

## 1. Engine Invariants

1. **Lightweight Execution:** Retain pure mathematical execution and minimal dependencies.
2. **Cryptographic Randomness:** Always use `crypto.randomInt` for rolling dice.
3. **Deterministic Tests:** Ensure all math and generator functions accept testable overrides or mocks for Jest.
4. **Generational Task Tracking:** All work items must be recorded in `.dev/2606/backlog.json`.
5. **GVS Versioning:** All release tags adhere strictly to GVS format (`[YYMM].[SUBVERSION].[REVISION]-[TAG]`).

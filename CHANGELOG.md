# Changelog - JLDN RPG Dice

All notable changes to the **RPG Dice** Pulsar package will be documented in this file.

The format is based on [Keep a Changelog 1.1.0](https://keepachangelog.com/en/1.1.0/),
and this project adheres to the [JLDN Generational Versioning Schema (GVS)](https://github.com/JLDesignNetwork/Generational-Versioning-Schema).

## [2606.2.0-s] - 2026-08-18

### Added
- **In-Repo Documentation Wiki (`docs/`)**: Established version-controlled documentation wiki (`docs/index.md`, `docs/architecture.md`, `docs/usage.md`, `docs/dice_engine.md`).
- **Generational Development Hub (`.dev/`)**: Established root `.dev/` generational hub containing `ROADMAP.md`, `backlog.json`, `2606/backlog.json`, and `2606/ideas.json`.
- **GitHub Governance Suite**: Scaffolded `.github/FUNDING.yml`, `.github/SECURITY.md` (contact `jldesignnetwork@icloud.com`), `.github/CONTRIBUTING.md`, `.github/CODE_OF_CONDUCT.md`, `.github/PULL_REQUEST_TEMPLATE.md`, `.github/copilot-instructions.md`, structured `.github/ISSUE_TEMPLATE/` forms, and automated CI workflows (`ci.yml`, `codeql.yml`).

### Changed
- **Security Hardening**: Replaced `Math.random` in `lib/engine.js` with Node's native `crypto.randomInt` cryptographically secure pseudo-random number generator (CWE-338 compliance).
- **Package Metadata**: Standardized package naming and GVS versioning `2606.2.0-s`.

## [2606.1.0-s] - 2026-06-12

### Added
- Initial genesis build: Inline dice rolling engine, Fate/Fudge dice support, and 3d6/4d6 ability score pool generators for Pulsar.

# Changelog

All notable changes to the CCE Ecosystem will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned

- **Cloud:** Custom date range analysis (Q2 2026)
- **Node:** Coinbase Pro support (Q2 2026)
- **Pocket:** Email notifications (Q2 2026)

## [1.0.0] - 2026-02-09

**The Genesis Release.**

The complete Cascade Compounding Engine ecosystem is now live.

### Added

#### CCE Cloud (v1.0)

- **Dashboard:** Live state tracking, performance metrics, and market context cards.
- **History:** Full playback of market cycles from 2013 to present.
- **Simulation:** Portfolio simulation with custom starting capital.
- **Infrastructure:** High-availability deployment on Vercel/Railway.

#### CCE Node (v1.0)

- **Hardware:** Raspberry Pi 5 image with pre-configured environment.
- **Engine:** Seven-state machine implementation (DORMANT to EXTRACTION).
- **Execution:** Binance Spot API integration for automated trading.
- **Security:** Local encrypted key storage (SQLite + Fernet).
- **Interface:** Local web dashboard (`http://cce-node.local`).

#### CCE Pocket (v1.0)

- **Mobile App:** Native iOS and Android applications.
- **Notifications:** Push alerts for state changes and trade execution.
- **Sync:** Dual-mode synchronisation (Cloud API + Local Node API).
- **Widgets:** Home screen widgets for quick status checks.

#### Documentation

- **Legal:** UK-compliant License Agreement and Privacy Policy.
- **Guides:** Comprehensive READMEs for all three products.
- **Onboarding:** Email sequences for new subscribers.

### Security

- Established `SECURITY.md` with responsible disclosure policy.
- Implemented encrypted local storage for Node API keys.
- Enforced read-only permissions for Pocket app.

# Contributing to the CCE Ecosystem

First off, thank you for your interest in the Cascade Compounding Engine.

The CCE is a **proprietary, disciplined system**. While the code is visible for transparency ("Cloud is proof"), it is not open-source in the traditional sense (MIT/Apache).

We welcome contributions that improve the **stability, clarity, and usability** of the ecosystem, provided they align with our philosophy: **Sovereign. Deterministic. Disciplined.**

---

## The Philosophy

Before contributing, understand what we are building.

1. **No Hype.** We do not predict prices. We do not promise returns.
2. **No Emotion.** The engine is deterministic.
3. **Sovereignty.** The user owns their keys and their hardware.

If your contribution adds "gamification," "social sharing," or "price prediction," it will be rejected.

---

## What We Accept

### 1. Bug Fixes

If you find a bug in the Node execution logic, the Cloud dashboard, or the Pocket app, please report it.

* **Security vulnerabilities:** Email `security@gibletscreations.com` immediately. Do not open a public issue.
* **Logic errors:** Open a GitHub Issue with a reproduction case.

### 2. Documentation

Clarity is part of our product.

* Typos, broken links, or confusing explanations in the docs are welcome fixes.
* Translations are welcome (please open an issue first).

### 3. Infrastructure & Tooling

* Scripts to help set up the Node on different hardware.
* Docker optimizations (for the dashboard).
* CI/CD improvements.

---

## What We Do NOT Accept

### 1. Strategy Modifications

The **Seven-State Machine** is the core intellectual property of Giblets Creations.

* We do **not** accept PRs that change the entry/exit conditions.
* We do **not** accept PRs that add new indicators (RSI, MACD, etc.) unless approved by the core team.
* The strategy is fixed.

### 2. "Features" that add Noise

* Price alerts for 1% moves.
* Confetti animations.
* Social leaderboards.
* Anything that increases anxiety or obsession.

---

## How to Submit

1. **Check Issues:** See if the discussion already exists.
2. **Open an Issue:** Before writing code, discuss your idea.
3. **Fork & Branch:** Create a branch for your fix.
4. **Submit PR:** Keep it small. Keep it clean.
5. **Sign the CLA:** By submitting a Pull Request, you agree that your contribution becomes the property of Giblets Creations and is licensed under the project's proprietary license.

---

## Style Guide

### Code

* **Python (Node/Backend):** Follow PEP 8. Type hints are mandatory.
* **React (Cloud):** Functional components. TypeScript preferred.
* **Swift/Kotlin (Pocket):** Follow platform standard guidelines.

### Tone

* **Documentation:** Professional, concise, British English (en-GB).
* **Commit Messages:** Imperative mood ("Fix bug", not "Fixed bug").

---

## Community

* **Discord:** `discord.gg/cce` (Subscribers only)
* **Support:** `support@gibletscreations.com`

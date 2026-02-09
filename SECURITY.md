# Security Policy

We take the security of the Cascade Compounding Engine (CCE) ecosystem seriously.

Because CCE Node executes real trades and CCE Cloud displays sensitive (simulated) data, trust is paramount. We appreciate the efforts of security researchers who help us keep our ecosystem safe.

---

## Reporting a Vulnerability

If you discover a security vulnerability in CCE Cloud, CCE Node, or CCE Pocket, please report it to us immediately.

**Do NOT open a public GitHub issue.**

### How to Report

**Email:** `security@gibletscreations.com`

Please include the following in your report:

1. **Product:** (Cloud, Node, or Pocket)
2. **Type:** (e.g., XSS, RCE, Authentication Bypass, API Key Leak)
3. **Severity:** Your assessment (Low / Medium / High / Critical)
4. **Proof of Concept:** Detailed steps to reproduce the issue.

### Our Response Timeline

We are a small, disciplined team. We prioritise security reports above feature work.

1. **Acknowledgment:** We will acknowledge your report within **48 hours**.
2. **Assessment:** We will validate the issue and determine impact within **5 business days**.
3. **Resolution:** We aim to release a fix within **30 days** (much sooner for critical issues).

---

## Scope

### In Scope

* **CCE Cloud:** `cloud.cce.gibletscreations.com`
* **CCE Node:** The execution engine software (Python/SQLite stack).
* **CCE Pocket:** The iOS and Android mobile applications.
* **Infrastructure:** API endpoints managed by Giblets Creations.

### Out of Scope

* **Social Engineering:** Phishing attacks against our employees or users.
* **Physical Attacks:** Gaining physical access to a user's Node device.
* **User Error:** Users leaking their own API keys or using weak passwords.
* **Third-Party Services:** Vulnerabilities in Binance, Cloudflare, Vercel, or Railway (please report to them directly).

---

## Safe Harbor

If you conduct security research in good faith and in accordance with this policy, Giblets Creations will:

* **Not** pursue legal action against you.
* **Not** suspend your account (provided it was used for testing purposes only).
* Work with you to understand and resolve the issue.

**Rules of Engagement:**

* Do not access or modify data that does not belong to you.
* Do not degrade the performance of our services (no DDoS).
* Use your own accounts/devices for testing.

---

**Thank you for helping us maintain a sovereign and secure ecosystem.**

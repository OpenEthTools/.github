# Security Policy

Security is the core product of OpenEthTools. We build open-source, offline-first utilities for the Ethereum ecosystem. This document outlines our global security philosophy and vulnerability reporting process.

## 1. Our Security Philosophy

We believe that trust in the crypto ecosystem should not be based on brand reputation, but on **verifiable code**. All our tools adhere to these three principles:

### 🛡️ Transparency & Auditable Code
We do not use minified or obfuscated code in critical security logic. Our repositories are structured to be easily readable by human auditors. We encourage every user to review the source code before usage.

### 🔌 Offline-First Architecture
Whenever possible, our tools are designed to run client-side (in your browser) without requiring a backend server. This ensures that sensitive data—such as private keys or seeds—never leaves your device.

### 📦 Minimal Dependencies
Supply chain attacks are a major risk in modern web development. We strictly limit our use of external npm packages and third-party libraries. We prefer "Zero-Dependency" implementations for cryptographic functions to reduce the attack surface.

## 2. Community Audits

While we internally review all code before publishing, we rely on the open-source community to verify our work.

* **Status:** Our repositories are open for public review.
* **Verification:** We recommend users cross-reference our releases with the source code on GitHub.
* **Bug Bounties:** While we do not currently have a funded bug bounty program, we provide public attribution and "Hall of Fame" credit to security researchers who responsibly disclose critical vulnerabilities.

## 3. Reporting a Vulnerability

We take all security reports seriously. If you find a vulnerability in any OpenEthTools repository, please follow this **Coordinated Disclosure Policy**:

1.  **Do NOT open a public GitHub Issue.** This prevents malicious actors from exploiting the bug before it is fixed.
2.  **Email us directly:** contact@openethtools.com
3.  **Include details:** Please provide a proof-of-concept or a description of the attack vector.

We aim to acknowledge receipt of your report within 48 hours and will keep you updated on the fix timeline.

## 4. Out of Scope

The following are considered out of scope for security reports:
* Phishing attacks imposter websites (though please let us know so we can report them).
* User error involving insecure storage of generated keys (e.g., saving keys to a cloud service).

---
*OpenEthTools - Verifiable. Offline. Open.*

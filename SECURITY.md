# Security Policy

## Overview

The Appropriation Strategy Lab is a client-side educational mini-game. It is a single HTML file that runs entirely in the browser: no accounts, no logins, no server-side components, and no personal data collected through gameplay. Game state exists only in the player's browser.

## Analytics (opt-in only)

The game includes Google Analytics for anonymous usage counting, and it is **off by default**:

- No analytics code loads until the player explicitly consents via the cookie banner
- Declining leaves the game fully functional, with no tracking of any kind
- Consent can be changed at any time via the "Change preference" link
- If consent is granted, IP anonymisation is enabled and standard Google Analytics processing applies

## For University IT and Data Protection Teams

- **No personal data is processed through gameplay.** No names, emails, student numbers, or accounts.
- **Analytics is strictly consent-based.** Nothing loads before an explicit opt-in, which satisfies the ePrivacy consent requirement; students who decline are not tracked at all.
- **No integration with university systems.** No LMS, no authentication, no licences. Students open a web page.
- **Fully auditable.** The complete source code is public in this repository, so every claim can be verified by inspection.
- **Offline option.** The HTML file can be downloaded and run locally or from institutional servers.

## Reporting a Vulnerability

If you discover a security issue, please report it responsibly.

**Email**: ammon.salter@wbs.ac.uk

Please include a description of the vulnerability, steps to reproduce it, and the potential impact. Do not open a public issue for security vulnerabilities. We will acknowledge receipt within 7 days and aim to address confirmed vulnerabilities promptly.

## What This Policy Does Not Cover

- Vulnerabilities in browsers, operating systems, or third-party services (GitHub Pages, CDNs)
- Issues arising from user modifications to the source code
- Gameplay bugs (please open a regular issue for those)

Thank you for helping keep this project safe.

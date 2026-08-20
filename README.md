# ECHORA
A website where anyone can report harassment or corruption completely anonymously — meaning no name, no email, no login is ever asked for or stored
#  (Echora) — Speak Up Without Fear, At Any Level

 A zero-trace, dual-path anonymous reporting platform for workplace harassment and civic corruption.

## Overview
SafeVoice is designed to remove the psychological and retaliatory barriers to reporting misconduct. By eliminating user authentication, stripping metadata/IP logs, and assigning verifiable tracking IDs, the platform enables secure, two-way anonymous communication.

##  Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Zero PII storage)
- **Security:** SHA-256 Hash Chaining for audit logs, client-side metadata stripping

##  Architecture & Features
- **Zero-Trace Submission:** No PII, cookies, or IP logging.
- **Smart Dual Routing:** Direct-to-organization (Internal HR) or Legal/Anti-Corruption guidance workflow.
- **Asynchronous Tracking:** Secret Case ID (e.g., `SV-4821`) for status verification and follow-ups.
- **Tamper-Proof Audit Trail:** Cryptographic hashing of state transitions.


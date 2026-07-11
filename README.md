# Digital Trust Score Calculator

A lightweight C console application that helps users evaluate their personal cybersecurity hygiene through a 10-point interactive assessment, then delivers a score, a security rating, and tailored recommendations.

## Overview

Most people have no simple way to gauge how "secure" their digital habits actually are. **Digital Trust Score Calculator** solves this with a quick, guided quiz covering the most common risk areas — password strength, 2FA usage, phishing awareness, backups, and more — and translates the answers into an easy-to-understand trust score.

## Features

- **10-step interactive assessment** covering:
  1. Password strength
  2. Two-Factor Authentication (2FA)
  3. Suspicious link avoidance
  4. Software updates
  5. Antivirus usage
  6. Backup practices
  7. Device lock (PIN/password/biometric)
  8. Public Wi-Fi safety
  9. Phishing awareness
  10. App permission review
- **Weighted scoring system** — each category contributes points toward a total Digital Trust Score.
- **Security level classification** — categorizes the user as **Low**, **Moderate**, or **High** security.
- **Personalized recommendations** — actionable tips based on the user's results.
- **General best-practice checklist** — a 10-point cybersecurity hygiene guide shown at the end.

## Tech Stack

- **Language:** C
- **Compiler:** MinGW-w64 (GCC 14.2.0)
- **Platform:** Windows (console application)

## How to Run

1. Download `DigitalTrustCalculator.exe`.
2. Run it from the command line or by double-clicking:
   ```
   DigitalTrustCalculator.exe
   ```
3. Answer each prompt (`1` for Yes, `0` for No, where applicable).
4. Review your Digital Trust Score, security level, and personalized recommendations.

## Sample Flow

```
=====================================================
        DIGITAL TRUST SCORE CALCULATOR
=====================================================
STEP 1: Password Strength Check
Enter your main account password:
Password Strength Score: ...

STEP 2: Two-Factor Authentication (2FA)
Do you enable 2FA? (1=Yes, 0=No):
...

Your Total Digital Trust Score: XX
Security Level: MODERATE

RECOMMENDATIONS
Your security level is moderate.
You are doing good but still need improvement.
```

## Roadmap / Planned Extensions

This project is actively being extended. Planned improvements include:

- [ ] **GUI version** (using a framework like Qt, WinForms, or a web front-end) to replace the console interface
- [ ] **Password strength engine** — real entropy-based scoring instead of a placeholder check
- [ ] **Score history & tracking** — save results over time to a local file or database
- [ ] **Export report as PDF/HTML** for sharing or record-keeping
- [ ] **Localization** — support for multiple languages
- [ ] **Cross-platform build** (Linux/macOS via CMake)
- [ ] **Web version** — reimplement as a browser-based tool for wider accessibility
- [ ] **Custom weighting** — let organizations adjust category weights for their own security policy

## Motivation

Cybersecurity awareness starts with self-assessment. This tool was built to make that first step simple, fast, and non-technical — no jargon, just clear questions and clear next steps.

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

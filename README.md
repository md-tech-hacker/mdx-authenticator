<div align="center">

# MDX AUTHENTICATOR

![MDX Authenticator](assets/banner.png)

**Secure authenticator codes, encrypted passwords, Android autofill, and a browser extension companion.**

[![Status](https://img.shields.io/badge/status-active-7c3aed?style=for-the-badge)](https://mdx-authenticator.app)
[![Android](https://img.shields.io/badge/Android-APK-success?style=for-the-badge)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Extension](https://img.shields.io/badge/Browser-Extension-blue?style=for-the-badge)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Security](https://img.shields.io/badge/security-encrypted%20vault-black?style=for-the-badge)](#security-model)

</div>

---

## Overview

**MDX Authenticator** is a mobile-first security app for authenticator codes,
password management, encrypted vault sync, password checkup, Android autofill,
recovery codes, and browser autofill.

Website: [mdx-authenticator.app](https://mdx-authenticator.app)

> This is the public download and release repository. Product source code is private.

---

## Download

| Package | Link |
| --- | --- |
| Android APK | [Open latest release](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest) |
| Browser extension ZIP | [Open latest release](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest) |

### Android APK

Download and install the APK from the latest release. The app appears on Android
as **Authenticator**.

### Browser extension

1. Download and extract `mdx-authenticator-extension.zip` from the latest release.
2. Open `chrome://extensions`.
3. Enable **Developer mode**.
4. Select **Load unpacked** and choose the extracted extension folder.
5. Open the extension popup and choose **Connect Extension**.

---

## Core features

| Category | Features |
| --- | --- |
| Authenticator | TOTP, HOTP, QR scan, manual setup key, 6 and 8 digit codes, countdown timer |
| Password vault | Encrypted passwords, notes, recovery codes, folders, custom fields, generator |
| Autofill | Android Autofill Service, save prompts, update prompts, browser suggestions |
| Security | App Password, biometric unlock, secure clipboard, screenshot protection |
| Sync | Encrypted Supabase sync, offline queue, profile separation, device activity |
| Browser extension | Chrome Manifest V3, secure Google connection, local unlock, autofill |

---

## Security model

- Google sign-in is used only for identity.
- App Password is used locally to unlock encrypted vault data.
- Passwords, OTP secrets, recovery codes, and App Passwords are never uploaded as plaintext.
- Supabase stores encrypted data and row-level security isolates each account.
- The website is only a landing page and connection API. There is no web vault or dashboard.

---

## Support

Visit [mdx-authenticator.app/support](https://mdx-authenticator.app/support).

Do not submit passwords, App Passwords, recovery codes, session tokens, or vault screenshots in issues.

<div align="center">
  <sub>MDX Authenticator</sub>
</div>

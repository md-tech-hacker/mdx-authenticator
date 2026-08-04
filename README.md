<div align="center">

# 🔐 MDX Authenticator

![MDX Authenticator](assets/banner.png)

**A secure authenticator, password vault, autofill, and encrypted sync companion.**

[![Status](https://img.shields.io/badge/status-active%20development-7c3aed?style=for-the-badge)](https://mdx-authenticator.app)
[![Android](https://img.shields.io/badge/Android-APK-success?style=for-the-badge)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Extension](https://img.shields.io/badge/Browser-Extension-blue?style=for-the-badge)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Security](https://img.shields.io/badge/security-zero--knowledge-black?style=for-the-badge)](#security-model)
[![Made by](https://img.shields.io/badge/made%20by-MD%20Tech%20Hacker-purple?style=for-the-badge)](https://github.com/MD-TECH-HACKER)

</div>

---

## ✨ Overview

**MDX Authenticator** is a premium mobile-first security app for authenticator
codes, password management, encrypted vault sync, password checkup, Android
autofill, recovery codes, and browser autofill.

> Developed by **『⛥ 𝗠𝗗 𝗧𝗘𝗖𝗛 𝗛𝗔𝗖𝗞𝗘𝗥 ⛥』**

Website/domain: **[mdx-authenticator.app](https://mdx-authenticator.app)**

> This public repository is for download packages and release notes. The product source is private.

---

## 🚀 Download

### 📱 Android APK

The latest Android APK is available in [GitHub Releases](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest).

The installed app name is **Authenticator**. Internal package and protocol identifiers remain MDX-based.

### 🧩 Browser Extension

The obfuscated browser extension ZIP is available in [GitHub Releases](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest).

1. Download `mdx-authenticator-extension.zip` and extract it.
2. Open `chrome://extensions`.
3. Turn on **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder.
5. Open the extension popup and choose **Connect Extension**.

---

## 🌟 Core Features

| Category | Features |
|---|---|
| 🔢 Authenticator | TOTP, HOTP, SHA1/SHA256/SHA512, 6/8 digit codes, QR scan, manual setup key, live countdown |
| 🔐 Password Vault | Encrypted passwords, custom fields, notes, recovery codes, folders, tags, strong password generator |
| 🧪 Checkup | Weak password scan, reused password scan, old password warnings, leaked password check |
| 📲 Autofill | Android Autofill Service, password save prompt, update prompt, biometric before fill |
| 🛡️ Security | App Password, biometric unlock, secure clipboard, screenshot protection, encrypted vault data |
| ☁️ Cloud Sync | Encrypted Supabase sync, offline queue, sync status, profile and device separation |
| 🧑‍💻 Browser Extension | Chrome Manifest V3, secure Google connection, local unlock, autofill and save prompts |

---

## 🔐 Security Model

- Google login is used only for identity.
- App Password is used locally to unlock and decrypt the vault.
- Passwords, OTP secrets, recovery codes, and App Passwords are never uploaded as plaintext.
- Supabase stores encrypted vault data and row-level security isolates each account.
- The website is a landing page and connection API only. There is no web vault or web dashboard.

---

## 🆘 Support

Visit [mdx-authenticator.app/support](https://mdx-authenticator.app/support).

Do not send passwords, App Passwords, recovery codes, session tokens, or vault screenshots in issues.

<div align="center">
  <sub>🔐 MDX Authenticator • 『⛥ 𝗠𝗗 𝗧𝗘𝗖𝗛 𝗛𝗔𝗖𝗞𝗘𝗥 ⛥』</sub>
</div>

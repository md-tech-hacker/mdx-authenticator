<div align="center">

# 🔐 MDX Authenticator

![MDX Authenticator](assets/banner.png)

**A secure authenticator, password vault, password checkup, autofill, and device approval system.**

[![Status](https://img.shields.io/badge/status-active%20development-7c3aed?style=for-the-badge)](#)
[![Android](https://img.shields.io/badge/Android-APK-success?style=for-the-badge)](#download-apk)
[![Extension](https://img.shields.io/badge/Browser-Extension-blue?style=for-the-badge)](#browser-extension)
[![Security](https://img.shields.io/badge/security-zero--knowledge-black?style=for-the-badge)](#security-model)
[![Made by](https://img.shields.io/badge/made%20by-MD%20Tech%20Hacker-purple?style=for-the-badge)](#credits)

</div>

---

## ✨ Overview

**MDX Authenticator** is a premium mobile-first security app for authenticator codes, password management, encrypted vault sync, password checkup, autofill, recovery codes, and trusted-device approval.

It is designed like a secure combination of Google Authenticator, Microsoft Authenticator, Proton Pass, Bitwarden, 1Password, and Apple Passwords — with MDX branding and a premium mobile UI.

> Developed by **『⛥ 𝗠𝗗 𝗧𝗘𝗖𝗛 𝗛𝗔𝗖𝗞𝗘𝗥 ⛥』**

Website/domain: **https://mdx-authenticator.app**

---

## 🚀 Core Features

| Category | Features |
|---|---|
| 🔢 Authenticator | TOTP, HOTP, SHA1/SHA256/SHA512, 6/8 digit codes, QR scan, manual setup key, live countdown |
| 🔐 Password Vault | Encrypted passwords, custom fields, notes, recovery codes, folders, tags, strong password generator |
| 🧪 Checkup | Weak password scan, reused password scan, old password warnings, missing 2FA, leaked password check |
| 📲 Autofill | Android Autofill Service, save password prompt, update password prompt, biometric before fill |
| 🛡️ Security | App Password, biometric unlock, auto-lock, screenshot protection, secure clipboard, rooted device protection |
| ☁️ Cloud Sync | Encrypted Supabase sync, offline queue, sync status, device list, conflict-ready architecture |
| 🧑‍💻 Web/Extension | Website plan, secure web dashboard, browser extension release structure |
| 🎨 UI | Premium dark glass mode, light mode, dark mode, system theme, blue/purple security style |

---

## 📱 Download APK

The latest Android APK will be available in **GitHub Releases**.

Local release folder:

```txt
releases/apk/
```

---

## 🧩 Browser Extension

Browser extension files will be released under:

```txt
releases/extension/
extension/
```

See [extension/README.md](extension/README.md).



---

## 🔐 Security Model

MDX Authenticator is designed around a **zero-knowledge encrypted vault** model.

### Important rules

- Google login is used only for identity.
- App Password is used to unlock/decrypt the vault.
- App Password is never stored as plaintext.
- Passwords are never uploaded as plaintext.
- OTP secrets are never uploaded as plaintext.
- Recovery codes are encrypted.
- Supabase stores only encrypted vault data.
- Decryption happens only on the client after secure unlock.
- Biometric unlock only unlocks trusted local key material on an already trusted device.

---

## 🔢 Authenticator

Supported authenticator features:

- TOTP and HOTP
- QR code scan
- Manual setup key
- `otpauth://` URL support
- SHA1 / SHA256 / SHA512
- 6-digit and 8-digit codes
- 30-second default period
- Custom period/counter support
- Tap to copy OTP
- Secret key reveal only after biometric/App Password
- Folder/profile support

---

## 🔐 Password Manager

Password vault features:

- Save website/app logins
- Website URL normalization
- Favicon/logo fetch
- Username, email, phone, password fields
- Unlimited custom fields
- Recovery codes per account
- Strong password generator
- Password strength meter
- Biometric reveal/copy
- Secure clipboard auto-clear
- Import Google Password Manager CSV
- Export encrypted `.mdxvault` backup

---

## 🧪 Password Checkup

Checkup can detect:

- Weak passwords
- Reused passwords
- Old passwords
- Missing 2FA
- Leaked passwords using Have I Been Pwned Pwned Passwords k-anonymity
- Ignored warnings and recheck flow

Password leak checks must never send plaintext passwords.

---

## 📲 Autofill

Android autofill plan:

- Android Autofill Service
- Autofill saved usernames/passwords in apps and Chrome
- Save password prompt
- Update password prompt
- Require biometric/App Password before filling
- Optional Accessibility helper for unsupported apps
- Optional overlay only when necessary

---

## 🛡️ Device Approval

MDX Authenticator supports trusted device approval:

1. User logs in with Google on a new device.
2. Existing trusted device receives approval request.
3. User approves/denies with biometric/App Password.
4. New device must still enter App Password to decrypt the vault.

---

## 📂 Repository Structure

```txt
mdx-authenticator/
  README.md
  LICENSE
  CHANGELOG.md
  releases/
    apk/
    extension/
  screenshots/
  assets/
  docs/
  extension/
```

---

## 📚 Documentation

- [Installation](docs/installation.md)
- [Security](docs/security.md)
- [Autofill](docs/autofill.md)
- [Recovery](docs/recovery.md)
- [Privacy Policy](docs/privacy.md)
- [Terms](docs/terms.md)

---

## 🛣️ Roadmap

- [ ] Android APK release
- [ ] Full mobile authenticator
- [ ] Password vault
- [ ] Android Autofill Service
- [ ] Secure backup/restore
- [ ] Device approval system
- [ ] Web dashboard at mdx-authenticator.app
- [ ] Chrome/browser extension

---

## 📝 Changelog

See [CHANGELOG.md](CHANGELOG.md).

---

## 👑 Credits

Developed by **『⛥ 𝗠𝗗 𝗧𝗘𝗖𝗛 𝗛𝗔𝗖𝗞𝗘𝗥 ⛥』**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

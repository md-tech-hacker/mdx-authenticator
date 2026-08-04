<div align="center">

# ðŸ” MDX Authenticator

![MDX Authenticator](assets/banner.png)

**A secure Android authenticator and browser-extension companion for passwords, codes, autofill, and encrypted vault sync.**

[![Android APK](https://img.shields.io/badge/Android-Download_APK-3ddc84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Browser Extension](https://img.shields.io/badge/Browser-Download_Extension-4285f4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest)
[![Website](https://img.shields.io/badge/Website-mdx--authenticator.app-ff6b16?style=for-the-badge&logo=googlechrome&logoColor=white)](https://mdx-authenticator.app)

[![Security](https://img.shields.io/badge/Security-Encrypted_Vault-111827?style=for-the-badge&logo=shield&logoColor=white)](#security-model)
[![Made by](https://img.shields.io/badge/Made_by-MD_Tech_Hacker-7c3aed?style=for-the-badge)](https://github.com/MD-TECH-HACKER)

</div>

---

## âœ¨ MDX Authenticator

MDX Authenticator is a mobile-first security app for authenticator codes,
encrypted passwords, Android autofill, recovery codes, and browser autofill.
Use the same Google account in the Android app and the browser extension.

> This public repository is for downloads and release notes. The product source
> code is private.

## ðŸš€ Download

| Download | What you get |
| --- | --- |
| [Android APK](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest) | Install the latest **Authenticator** APK on Android. |
| [Browser extension ZIP](https://github.com/MD-TECH-HACKER/mdx-authenticator/releases/latest) | Obfuscated Chrome extension package for manual installation. |
| [Website](https://mdx-authenticator.app) | Product information, support, security information, and download links. |

### Install the browser extension

1. Download `mdx-authenticator-extension.zip` from the latest release and extract it.
2. Open `chrome://extensions` in Chrome or another Chromium browser.
3. Turn on **Developer mode**.
4. Choose **Load unpacked** and select the extracted folder.
5. Open the extension popup and choose **Connect Extension**.

## ðŸ“± Android app

- TOTP and HOTP authenticator codes
- QR scanning and manual setup keys
- Encrypted password vault, notes, recovery codes, and folders
- Android Autofill Service and password-save prompts
- App Password, biometric unlock, secure clipboard, and screenshot protection
- Encrypted Supabase sync and offline-aware updates

The installed Android app name is **Authenticator**. Internal package and
protocol identifiers intentionally remain MDX-based.

## ðŸ§© Browser extension

- Chrome Manifest V3 extension
- Google account connection through the official MDX website
- Local App Password unlock before autofill
- Website matching, credential suggestions, strong-password generation, and save prompts
- The release ZIP is obfuscated for distribution; source code is private

## ðŸ” Security model

- Google sign-in is used for identity only.
- Vault data is encrypted before sync; no plaintext passwords or OTP secrets are uploaded.
- The App Password is used locally to unlock encrypted vault data and is never sent to the website.
- Supabase row-level security isolates every user's encrypted rows.
- The website is a landing page and API bridge only. There is no web vault or web dashboard.

## ðŸ†˜ Support

Visit [mdx-authenticator.app/support](https://mdx-authenticator.app/support).

Do not send passwords, App Passwords, recovery codes, browser tokens, or full
screenshots of your vault in an issue or support request.

---

<div align="center">
  <sub>Built by MD Tech Hacker â€¢ MDX Authenticator</sub>
</div>

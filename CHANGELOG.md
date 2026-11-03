# Changelog

All notable changes to MDX Authenticator will be documented here.

## Android build 24 — custom website icon fix

- Fixed icon lookup for custom websites, including mdx-server.me, by using the full normalized HTTPS site address.
- Clearing a website URL clears its saved domain; replacing it does not retain another website's cached icon.
- Icon sizes, bundled logos and offline caching are retained.
- 246 mobile tests, TypeScript and GitHub CI pass. Release signing and package checks pass; physical Android upgrade and biometric tests remain unperformed.
- Download [Android build 24](https://github.com/md-tech-hacker/mdx-authenticator/releases/tag/v1.0.0-build24). Older APK assets have been retired from public downloads.


## Android build 23 — website icons and sidebar

- Unfamiliar website links can retrieve a favicon and save it locally for offline reuse.
- Known service icons remain bundled; icon downloads never block access to codes.
- The sidebar follows a rightward swipe from the left edge and closes with a leftward swipe.
- Website icon lookup sends only the public hostname to Google's favicon service;
  see the [privacy policy](https://mdx-authenticator.app/privacy).
- Source validation: 245 mobile tests, TypeScript and Android Hermes export pass.
- Download [Android build 23](https://github.com/md-tech-hacker/mdx-authenticator/releases/tag/v1.0.0-build23). Earlier APK downloads do not include these changes.

## Authenticator-only update — 2026-11-02

- Dedicated offline Android authenticator with encrypted local storage.
- Device authentication, Google profile display and encrypted Supabase backup.
- Countdown resume fix, cloud status indicator and offline service logos.
- Public documentation and downloads now focus on the Authenticator app.
- Historical release notes below describe earlier versions.

## [1.0.0] - Upcoming

Initial release history is preserved in Git tags. Use the current documentation
and each APK's release notes when installing or upgrading.


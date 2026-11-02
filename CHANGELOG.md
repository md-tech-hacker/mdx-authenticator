# Changelog

All notable changes to MDX Authenticator will be documented here.

## Next Android build — website icons and sidebar

- Unfamiliar website links can retrieve a favicon and save it locally for offline reuse.
- Known service icons remain bundled; icon downloads never block access to codes.
- The sidebar follows a rightward swipe from the left edge and closes with a leftward swipe.
- Website icon lookup sends only the public hostname to Google's favicon service;
  see the [privacy policy](https://mdx-authenticator.app/privacy).
- Source validation: 245 mobile tests, TypeScript and Android Hermes export pass.
- These changes belong to production build 23. Earlier APK downloads do not include them.

## Authenticator-only update — 2026-11-02

- Dedicated offline Android authenticator with encrypted local storage.
- Device authentication, Google profile display and encrypted Supabase backup.
- Countdown resume fix, cloud status indicator and offline service logos.
- Public documentation and downloads now focus on the Authenticator app.
- Historical release notes below describe earlier versions.

## [1.0.0] - Upcoming

Initial release history is preserved in Git tags. Use the current documentation
and each APK's release notes when installing or upgrading.

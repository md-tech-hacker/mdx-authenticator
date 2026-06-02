# Security — MDX Authenticator

MDX Authenticator is designed with a zero-knowledge vault model.

## Core rules

- App Password is never stored as plaintext.
- Passwords are encrypted before cloud sync.
- OTP secrets are encrypted before cloud sync.
- Recovery codes are encrypted.
- Supabase stores encrypted blobs only.
- Decryption happens on the client after unlock.

## Sensitive actions

Require App Password or biometric:

- Reveal password
- Copy password
- Show authenticator setup key
- Export vault
- Delete item
- Reset vault
- Approve new device

## Device security

Planned protections:

- Screenshot blocking
- Recent app preview hiding
- Auto-lock on background
- Secure clipboard clearing
- Rooted device protection
- Trusted device approval

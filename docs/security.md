# Security

Authenticator stores accounts locally using AES-256-GCM with a device-only key
protected by Android Keystore-backed storage. Optional App Lock uses strong
biometrics or the device PIN, pattern or password. Setup-key disclosure and
account export require fresh device verification.

Optional Supabase snapshots are encrypted before upload. Google sign-in
identifies the owner; access rules isolate account backups. Supabase Vault
protects an account-recoverable cloud key. Authorized backend administrators
can access it: cloud backup is not zero-knowledge encryption.

See [the current security model](https://mdx-authenticator.app/security).
Never include setup keys, QR codes or tokens in vulnerability reports.

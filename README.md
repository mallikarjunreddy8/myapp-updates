# My App / Amrita BTech — app updates

Small signed update packs for the Amrita BTech app (Amrita Bengaluru B.Tech students).

- **Amrita-BTech-Classmates.apk** — install this once on Android (allow "install unknown apps"; if Play Protect asks, tap *More details → Install anyway*).
- After that the app updates itself: it downloads `manifest.json` + a ~0.5 MB `myapp-update-*.zip`, checks the signature, and asks you to tap **Restart**.

Packs are signed with an Ed25519 key that never leaves the maker's PC; the app refuses any pack that is not signed with it.
No student data is stored here.

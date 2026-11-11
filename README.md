# AYA Wallet - official releases

Official Android builds of AYA Wallet for people who cannot use Google Play.
This repository holds release files and checksums only. Prefer the stores:

- Google Play: https://play.google.com/store/apps/details?id=com.brunokapital.aya
- All apps: https://ayacoin.online/

## Verify before installing

1. File checksum must match `SHA256SUMS`:
   `shasum -a 256 aya-wallet-android-14.apk`
2. Signing certificate must be the Google Play app signing key:
   `apksigner verify --print-certs aya-wallet-android-14.apk`
   expected `Signer #1 certificate SHA-256 digest`:
   `bb50338eda4e9a0e7d3990a2023971d4632d0e6478d49aff2bc11304b0a73de3`
   (the same key is published at https://ayacoin.online/.well-known/assetlinks.json)
3. Package name: `com.brunokapital.aya`

If any check fails, do not install.

## Safety

- Download the APK only from the Releases of this repository.
- Your wallet lives only in the AYA app on your device. Never type your recovery phrase on any website.

## Releases

| Version | Build | File | SHA-256 | Date |
|---|---|---|---|---|
| 9 | 14 | aya-wallet-android-14.apk | b78330c42416cc31fecfa8aca4bdfb6d997a7b5027ab9a8ebd6242dea9ddb630 | 2026-11-11 |

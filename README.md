# Viotus Calculator releases

Public, cryptographically signed update channel for Calculator.

This repository contains release manifests only. Installers and updater archives are attached to
GitHub Releases. Source code, signing keys, credentials, customer data and licence data never belong
here.

- `live/latest.json` is the stable customer channel.
- `test/latest.json` is the Calculator Test channel.

The desktop app verifies every update archive against its embedded channel-specific public key
before installation.

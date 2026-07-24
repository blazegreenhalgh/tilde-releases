# Wayfinder Releases

This repository hosts the official public releases and automatic-update feed for **Wayfinder**, a modern file explorer for macOS.

Wayfinder’s application source code is maintained separately. This repository contains only compiled release files, update metadata, and release notes.

## Download Wayfinder

[Download the latest release](../../releases/latest)

Current system requirements:

- macOS 26 or later
- Apple Silicon Mac

## Installation

1. Download the latest `Wayfinder.dmg`.
2. Open the downloaded disk image.
3. Drag **Wayfinder** into your Applications folder.
4. Open Wayfinder from Applications.

Wayfinder is signed with an Apple Developer ID certificate and notarized by Apple.

## Automatic updates

Wayfinder uses [Sparkle](https://sparkle-project.org/) to check for and install updates securely.

After installing Wayfinder, you can manually check for updates from:

**Wayfinder → Check for Updates…**

Updates are verified using both Apple code signing and a dedicated Sparkle EdDSA signing key before installation.

## Release files

This repository may contain:

- Signed and notarized Wayfinder disk images
- `appcast.xml`, used by Sparkle
- Release notes
- Sparkle delta updates

Do not download files from unofficial mirrors or third-party websites.

## Support

If you encounter a problem, please open an issue in this repository and include:

- Your macOS version
- Your Wayfinder version
- What you were doing when the problem occurred
- Any relevant screenshots or error messages

Please do not include passwords, private files, API keys, or other sensitive information.

## Security

If you believe you have found a security issue, please do not disclose it in a public issue. Contact the developer privately instead.

---

Copyright © 2026 Blaze Greenhalgh Stewart. All rights reserved.

# OkayEver Android app

This repository contains the branded Android wrapper for the live OkayEver websites and an automated workflow that builds an installable APK.

The workflow packages only Android app source and the OkayEver brand assets. It does not include website PHP source, SQL backups, passwords, or payment secrets.

On each push to `main`, GitHub Actions builds a debug APK and stores it as the `OkayEver-APK` workflow artifact. For public distribution, create a signed release APK with a securely retained signing key.

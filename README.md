# Bored Physio Guitar Android releases

Official APK update channel for Bored Physio Guitar: an offline guitar tuner and chord library for Android 8.0 or later.

Download APKs from Releases. Each release includes app-debug.apk (a signed, non-debuggable release APK), update.json, SHA256SUMS, the public signer certificate and verification.json. Android always asks you to approve installation. This repository contains delivery information and release assets only.

## Update from 0.0.2 to 0.0.3

Version 0.0.2 does NOT have a repository preconfigured. Open Home → App updates, enter `https://github.com/Zilvis0/bored-physio-guitar-updates`, tap Save repository, then Check for updates. Choose Download for 0.0.3, then Install. If Android requires permission to install from this app, allow it in settings, return and tap Install again. Approve Android's installer. Do not uninstall 0.0.2; both releases use the same dedicated signing key.

Version 0.0.3 has this repository configured by default and supports quiet daily metadata checks. Downloading and installation still require your choices. If you install the latest 0.0.3 APK directly, the updater correctly reports no newer version.

The older 0.0.1 APK used a different debug signer. Only users still on 0.0.1 need a one-time uninstall before manually installing a dedicated-key version; this resets local preferences.

Public signing certificate SHA-256:

`f8c980ceed4ff6db08660b9e47eeecba30ab457f665b0516eff087f73e6f9b53`

Private signing material, credentials and development source are never release assets. Physical phone behavior must be verified by installing and testing on the device.

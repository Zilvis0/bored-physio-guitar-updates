# Bored Physio Guitar Android releases

Official APK update channel for Bored Physio Guitar: an offline guitar tuner and chord library for Android 8.0 or later.

Download APKs from Releases. Each release includes app-debug.apk (a signed, non-debuggable release APK), update.json, SHA256SUMS, the public signer certificate and verification.json. Android always asks you to approve installation. This repository contains delivery information and release assets only.

## Update from 0.0.2

Version 0.0.2 does NOT have a repository preconfigured. Open Home → App updates, enter `https://github.com/Zilvis0/bored-physio-guitar-updates`, tap Save repository, then Check for updates. Choose Download for the latest version (currently 0.0.5), then Install. If Android requires permission to install from this app, allow it in settings, return and tap Install again. Approve Android's installer. Do not uninstall 0.0.2; all releases from 0.0.2 onward use the same dedicated signing key.

Versions 0.0.3 and later have this repository configured by default and support quiet daily metadata checks. Downloading and installation still require your choices. The latest release is 0.0.5 (code 5), adding Strumming Coach and Metronome: 40–200 BPM, six patterns with arrows/rests, count-in, visual timeline, repeat and local rhythm history. Practice options include continuous listening-only playback and optional wired/USB-headphone microphone timing feedback. Speaker/Bluetooth exercises remain unscored. Audio never identifies down/up direction or chord identity. Missing timing confidence produces an unscored result.

From 0.0.4, open App updates → Check for updates → Download → Install, then approve Android's installer. Do not uninstall or clear storage: the package/signing identity and existing histories/preferences are retained. Physical-phone microphone, audio routing and latency testing remain necessary; no such tests are claimed by publication.

The older 0.0.1 APK used a different debug signer. Only users still on 0.0.1 need a one-time uninstall before manually installing a dedicated-key version; this resets local preferences.

Public signing certificate SHA-256:

`f8c980ceed4ff6db08660b9e47eeecba30ab457f665b0516eff087f73e6f9b53`

Private signing material, credentials and development source are never release assets. Physical phone behavior must be verified by installing and testing on the device.




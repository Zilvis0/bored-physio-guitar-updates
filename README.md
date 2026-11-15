# Bored Physio Guitar Android releases

Official APK update channel for Bored Physio Guitar: offline tuner, chord trainer, Strumming Coach and Metronome for Android 8.0 or later.

Latest: **0.0.6 (code 6)** — audible strumming demonstrations. In Strumming Coach, choose a pattern/chord/BPM and tap **Listen to Example**, **Slow Demo** (half tempo) or **Play Along** (loops). Metronome clicks toggle independently. Sounds are original chord-specific plucked-string synthesis, not commercial recordings or external samples. Demonstrations and play-along never capture or score microphone audio; normal microphone practice remains separate. No physical-phone audio-quality or latency validation is claimed by publication.

## Update in place

Versions 0.0.3 and later already know this repository. App updates → Check for updates → Download → Install, then approve Android's installer. Do not uninstall or clear storage: the package/signing identity and existing histories/preferences are retained.

Version 0.0.2 does NOT have a repository preconfigured. In Home → App updates enter `https://github.com/Zilvis0/bored-physio-guitar-updates`, tap Save repository, then Check for updates. Returning from installation-source permission settings requires tapping Install again.

Only the old 0.0.1 debug-signed build requires a one-time uninstall before a dedicated-key version. All releases from 0.0.2 onward use the same dedicated identity.

Each release provides only app-debug.apk (a signed, non-debuggable release APK), update.json, SHA256SUMS, the PUBLIC signer certificate and verification.json, plus release notes. This repository's source tree contains only this delivery README. Development source, private keys, passwords and private configuration are never uploaded.

Public signing certificate SHA-256:

`f8c980ceed4ff6db08660b9e47eeecba30ab457f665b0516eff087f73e6f9b53`

## Hear the example

Try Em, then G or C to hear different chord notes. Slow Demo preserves pitch while halving tempo. Rests omit new strums; existing strings may ring. Pause/resume repeats the unfinished measure; Play Along resumes on beat 1. Stop, navigation away, backgrounding, focus loss and headphone removal pause or release playback. Verify audio quality, accents, synchronization and headphone-disconnection behavior on your phone; automated scheduling tests do not establish physical acoustic quality.

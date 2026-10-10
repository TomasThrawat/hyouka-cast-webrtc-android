# Hyouka Cast WebRTC Android plugin

Android-only fork of `flutter_webrtc` `1.6.2+hotfix.4`.

## Capture changes
- Requests up to 60 frames per second for screen mirroring.
- Caps the long display edge at 1280 px and short edge at 720 px while preserving portrait/landscape aspect ratio to reduce encoder/decoder load and lag.
- Actual frame rate depends on display refresh, hardware encoding/decoding, thermal conditions, and Wi-Fi.
- System playback-audio capture is not yet implemented in this fork.

## Upstream and license
Based on https://github.com/flutter-webrtc/flutter-webrtc. See LICENSE.

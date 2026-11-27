# PairDrop Universal

Experimental Android 16 (API 36) compatibility build of [PairDrop Android](https://github.com/fm-sys/pairdrop-android), based on v2.3.1.

- Minimum SDK: 21 (Android 5.0).
- Target and compile SDK: 36 (Android 16).
- No maximum SDK declared.
- Separate application ID for coexistence with upstream.
- Debug-signed APK for testing only.

The workflow fetches upstream source, applies the build configuration changes, runs unit tests and builds an APK. Download the APK and corresponding modified source from the Actions run artifacts.

Installation and runtime compatibility are not guaranteed until tested on physical devices, including file sharing, storage, WebRTC, WebView, edge-to-edge and Android 16 behavior. Debug signing keys may change between builds; uninstalling the previous test build may be necessary.

Upstream licensing and copyright notices are retained in the source artifact. This is an independent experimental build, not an official PairDrop release.

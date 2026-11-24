# BUGTI EDITZ

Android photo and video editor with AI enhancement, FX effects picker, Curve/Regular speed editor, 18 filter categories, clip transitions, transform/crop/rotate/fit tools, 300% audio boost, 100 offline stickers, 100 fonts, and cloud project sync.

## Direct APK Download (Chrome)

[Download Bugti-Editz.apk directly](https://github.com/drayazbugti/Bugti-Edits-App/releases/latest/download/Bugti-Editz.apk)

- **APK file:** [`Download/Bugti-Editz.apk`](https://github.com/drayazbugti/Bugti-Edits-App/raw/main/Download/Bugti-Editz.apk)
- **HTML download page:** [`Download/index.html`](./Download/index.html)

## Automated GitHub Actions APK Build & Release

Every push to `main` or `master` runs the automated GitHub Actions build pipeline, which:

1. Decodes `debug.keystore.base64` to `debug.keystore` and prepares `.env` from `.env.example`.
2. Builds the Android APK (`gradle :app:exportApkToDownload`) into `Download/Bugti-Editz.apk`.
3. Uploads `Bugti-Editz.apk` as a build artifact and attaches it to the permanent `latest` GitHub Release.

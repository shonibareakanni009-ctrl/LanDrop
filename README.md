# LanDrop

Xender-style Android app: share files and APKs over local Wi‑Fi.  
**Receiver only needs a browser** (open the IP/QR link).

## Features
- Pick any files
- Share installed apps as APK
- Local HTTP server + QR code
- Mobile dark UI (XML layouts)
- Works without internet (same Wi‑Fi)

## Build
Open the project in Android Studio, or use GitHub Actions (see Actions tab).

### GitHub secrets (for signed release)
- `KEYSTORE_BASE64`
- `KEY_ALIAS`
- `KEY_PASSWORD`
- `STORE_PASSWORD`

## How to use
1. Open LanDrop on your phone
2. Add files or share an installed app
3. Tap **Start Sharing**
4. Other person scans the QR or opens the link in a browser on the same Wi‑Fi
5. They download – no app needed on their side

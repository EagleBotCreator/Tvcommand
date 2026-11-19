# TV Command (Android + Android TV)

Experimental Kotlin source project for an owner-controlled file receiver on Android TV.

The full Android Studio project is stored in [tvcommand-src.tar.xz](tvcommand-src.tar.xz). The GitHub Actions workflow extracts the archive, runs the shared-core unit tests, and builds separate phone and TV **debug APKs**.

Open the **Actions** tab and select a successful **Build TV Command APKs** run to download:
- `TVCommand-Phone-debug-APK`
- `TVCommand-TV-debug-APK`

**Prototype limitations:** no QR pairing, guest accounts, TV-side per-upload approval, automatic APK installation, or security audit. Use only on a trusted private LAN with port 39047 not exposed to the internet. The original Android files are inside the source archive, with `docs/BUILD_STATUS.md` and `docs/FOSS_REFERENCE.md`.

The source archive was repackaged from a prior conversation artifact and has not yet passed an Android SDK build. The build workflow will establish whether it compiles.
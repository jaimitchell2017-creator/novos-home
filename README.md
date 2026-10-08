# NOVA Home — Android starter

A first installable Android APK project for the NOVA Home smart-display concept.

## What this starter includes
- A polished dark, futuristic dashboard designed for a tablet.
- Scrollable Home, Photos, News, Weather, Browser, Maps, Apps, and Settings screens.
- Working in-app navigation and sample content.
- Android WebView shell so the interface runs as an APK.
- GitHub Actions workflow to build a debug APK automatically.

## Important current limitations
This is the **first UI/build milestone**, not the finished assistant. The AI chat is a clearly labelled demo interface; a local language model has not yet been bundled. The browser uses an embedded WebView and some sites (especially streaming services and Google Maps) may refuse to work inside it. Continuous “Hey Nova” wake-word detection, full email integrations, notification reading, and phone-call routing need additional native Android implementation and permission testing.

## Build with GitHub Actions
1. Create a GitHub repository for this project.
2. Upload/extract the contents of this ZIP so `settings.gradle`, `build.gradle`, `app/`, and `.github/` are at the repository root.
3. Open **Actions** and enable workflows if GitHub asks.
4. Choose **Build NOVA Home APK** and click **Run workflow**, or push a commit to `main`.
5. When the workflow finishes, open the run and download the `NOVA-Home-debug-APK` artifact.
6. On the tablet, download the APK and open it. Android may ask you to allow installation from that browser/file manager.

The debug APK is for testing. A release APK for distribution should be signed securely before sharing publicly.

## App identity
Package name: `com.novos.home`
Display name: `NOVA Home`

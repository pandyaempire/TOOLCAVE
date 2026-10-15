TOOLCAVE — 25 TOOLS STARTER

Files:
- index.html: responsive tool hub with 25 tools
- manifest.webmanifest, sw.js, icon.svg: basic PWA assets
- firebase-config.js: placeholder config for Google login
- FIREBASE_SETUP.txt: configure Google sign-in and encrypted cloud backup
- FIRESTORE_RULES.txt: private per-user Firestore rules
- PLAY_STORE_GUIDE.txt: Android/Play Store next steps

FASTEST TEST
Open index.html in a modern browser to test the local tools. For secure vault encryption and Google login, use HTTPS or localhost; file:// pages can restrict crypto/auth features. Google sign-in is intentionally disabled until Firebase config is filled in.

LOCAL STORAGE NOTE
Local data is stored in the current browser/device and can be removed by clearing browser data or uninstalling the app. Export encrypted vault backups regularly. Cloud backup requires Firebase setup and user sign-in.

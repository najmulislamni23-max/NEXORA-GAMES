NEXORA GAMES — GitHub Actions build package

This project includes a GitHub Actions workflow that can build a DEBUG APK in the cloud.
It is not a signed Play Store release AAB.

PHONE STEPS:
1. Create a GitHub repository named NEXORA-GAMES (Public or Private).
2. Upload the CONTENTS of this folder to the repository root. Make sure the hidden
   .github/workflows/android.yml file is included. If your phone's file picker hides
   .github, use GitHub website: Add file > Create new file and create
   .github/workflows/android.yml, then paste the workflow from this package's file.
3. Open the repository's Actions tab.
4. Select "Build NEXORA GAMES APK" and press "Run workflow", or wait for push build.
5. When the workflow is green, open the run and download the artifact named
   NEXORA-GAMES-debug-apk. Extract the artifact ZIP to get app-debug.apk.

IMPORTANT:
- This APK is a DEBUG/testing build, not the signed AAB required for Google Play.
- Test ads use Google's sample IDs and do not earn money.
- Before public release, replace sample AdMob IDs with your own, complete consent/privacy
  setup, test the app, create a signed release AAB, and meet current Play Console rules.
- Never click your own live ads.
- This is a casual virtual-points game only; points have no cash value.

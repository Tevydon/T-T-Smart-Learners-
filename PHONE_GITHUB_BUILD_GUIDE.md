# T & T Smart Learners — Phone APK Build

This project is configured to build the existing V3.0.8a app as an Android APK using GitHub Actions.

## Phone-only steps

1. Create a GitHub repository.
2. Upload the contents of this project to the repository (not the ZIP file itself).
3. Make sure `.github/workflows/build-apk.yml` is uploaded.
4. Open the repository's **Actions** tab.
5. Select **Build T&T Smart Learners APK**.
6. Tap **Run workflow**.
7. Wait for the workflow to finish with a green check.
8. Open the completed workflow and download the artifact named **TT-Smart-Learners-APK**.
9. Extract the downloaded artifact if necessary and install `app-debug.apk` on your Android phone.

The APK produced by this workflow is a debug APK intended for testing/installing on your device.

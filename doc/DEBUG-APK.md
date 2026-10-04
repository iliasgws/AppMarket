# Debug APK build

The Android debug APK is produced by GitHub Actions using `./gradlew :app:android:assembleDebug`.

Go to [Actions](../../actions), open the latest **Android Debug APK** run, and download the `AppMarket-debug-apk` artifact after the workflow succeeds. Extract the downloaded ZIP to get the installable APK.

This is a **debug build**, signed using the CI runner's debug key. It is not a release-signed APK. Upgrading later from a different signing key may require uninstalling the debug build first.

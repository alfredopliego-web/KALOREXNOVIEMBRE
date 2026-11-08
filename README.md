# KalorEx Smart Demo 1.0

Android demo app in Kotlin + Jetpack Compose. Includes simulated temperature ramp, target temperature slider, animated flame at target, weekly schedule editor, and simulated power/WiFi state.

**Demo only:** does not connect to ESP32 or control any water heater.

## Build APK
1. Open this folder in Android Studio (recent version).
2. Let Gradle sync and install Android SDK Platform 35 if prompted.
3. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. APK output: `app/build/outputs/apk/debug/app-debug.apk`.

Minimum Android: 8.0 (API 26). Application ID: `com.kalorex.smartdemo`.

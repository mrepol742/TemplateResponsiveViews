# TemplateResponsiveViews

Responsive views using fragments, bottom navbar on portrait sizes and navigation drawer on landscape sizes with floating action buttons.

# Requirements
- min sdk of 24 target sdk of 34 adjust accordingly to your needs
- Android Studio Giraffe
- Kotlin DSL v8.1.2

# Build

**Debug**
```
./gradlew assembleDebug
```

**Release**
```
./gradlew assembleRelease
```

# Install
Install using adb connected devices

**Debug**
```
adb install app/build/outputs/apk/debug/debug.apk
```

**Release**
```
adb install app/build/outputs/apk/release/release.apk
```
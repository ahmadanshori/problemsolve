## Syntax

Jalankan ios dengan spek emulator yang diinginkan
```groovy
react-native run-ios --simulator="iPhone X"
```
Run Android Production
```groovy
react-native run-android --variant release
```
android:prod
```groovy
cd android && ./gradlew clean && ./gradlew assembleRelease
```
android:staging
```groovy
cd android && ./gradlew clean && ./gradlew assembleReleaseStaging
```
Log Android
```groovy
react-native log-android
```

## Problem Solve error2 di Xcode

| Error   |      Solution      |
|----------|-------------|
|library not found for -lPods-OneSignalNotificationServiceExtension|pod install ulang|
|invalid app store icon. the app store icon in the asset catalog in ‘eyelovin.app’ cant be transparent|buka gambar => export => uncheck Alpha => save upload ulang|
|the following URL schemes found in your app are not in the correct format|create cer|
|sign in unable to resolve an issue with|buat signing sesuai build identifier|
|the following URL schemes found in your app are not in the correct format|create cer|

## Adobe XD Link
- [iProfile](https://xd.adobe.com/view/cf084c89-e2c2-4947-8e91-8b59e7c5330c-9a5b/)

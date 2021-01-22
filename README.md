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

## Adobe XD Link (prototype)
- [iProfile](https://xd.adobe.com/view/cf084c89-e2c2-4947-8e91-8b59e7c5330c-9a5b/)
- [Eyelovin](https://xd.adobe.com/view/e2cf2909-1097-4afd-59ec-339c3befed65-94fe/)
- [Xendtral Driver](https://xd.adobe.com/view/166870d3-bb3b-467d-be65-6c46a747d5af-433b/)
- [Xendtral Courier](https://xd.adobe.com/view/38a4c160-4014-415e-7d2c-64737ee70287-4e95/screen/4145b585-3bda-4aab-aa5f-e3471921181f/?fullscreen)
- [iTMG](https://xd.adobe.com/view/bd0ad450-c87c-4a3e-469c-b446d10c2a96-cb3b/)

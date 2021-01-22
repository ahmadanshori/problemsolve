## Syntax

#### Jalankan ios dengan spek emulator yang diinginkan
```groovy
react-native run-ios --simulator="iPhone X"
```

#### Run Android Production
```groovy
react-native run-android --variant release
```

#### android:prod
```groovy
cd android && ./gradlew clean && ./gradlew assembleRelease
```

#### android:staging
```groovy
cd android && ./gradlew clean && ./gradlew assembleReleaseStaging
```

#### Log Android
```groovy
react-native log-android
```


## Problem Solve error2 di Xcode

| Error   |      Solution      |
|----------|-------------|
|library not found for -lPods-OneSignalNotificationServiceExtension|pod install ulang|
|invalid app store icon. the app store icon in the asset catalog in ‘eyelovin.app’ cant be transparent|buka gambar => export => uncheck Alpha => save upload ulang|

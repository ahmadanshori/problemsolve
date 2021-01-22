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


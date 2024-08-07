# Documentsui-shortcut

Create shotcut to open system's native file exporer  
using `content://com.android.externalstorage.documents/root/primary` with `android.intent.action.VIEW`

support package name:  

- com.android.documentsui
- com.google.android.documentsui

## Build the app

```shell
./gradlew build
```

Generates an apk with a self-signed signature

## Install the app

```shell
adb install app/build/outputs/apk/release/app-release.apk 
```

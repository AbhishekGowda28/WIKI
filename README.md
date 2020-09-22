# WIKI
My own WIKI


## Ubuntu Notes

- starting display at 
    ```bash
    export DISPLAY=localhost:0.0
    ```


## Links to Repos

- [Dev Tools detection](https://github.com/sindresorhus/devtools-detect)

## Uninstall Bootloaders from Android
 - Enable developers mode
 - Enable USB debugging
 - Download [ADB](https://developer.android.com/studio/releases/platform-tools)
 - Add ADB to environment path
 - Install APP Inspector
 - Install APK Downloader to backup the apk files
 - Open ADB Shell
 ```shell
  adb shell

  pm list package | grep "package-name"

  pm uninstall -k --user 0 "package-name"
  E.g.  pm uninstall -k --user 0 'com.google.android.apps.youtube'
 ```

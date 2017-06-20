## Windows 設定 Android Sdk 環境變數

打開你的CMD

```
➤ setx ANDROID_HOME "%USERPROFILE%\AppData\Local\Android\Sdk"
```

這是 Android Studio 預設安裝目錄，如果有更換過安裝的目錄將需要修改此目錄

```
➤ setx ANDROID_HOME "<insert your android sdk path>"
```

接下來我們要在 path 環境變數中加入 adb 指令的目錄

```
➤ setx path "%path%;%ANDROID_HOME%\platform-tools"
```
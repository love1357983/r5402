## Windows 設定 Android Sdk 環境變數

打開你的CMD

```
➤ setx ANDROID_HOME "%USERPROFILE%\AppData\Local\Android\Sdk"
```

這是 Android Studio 預設安裝目錄，如果有更換過安裝的目錄將需要修改此目錄

```
➤ setx ANDROID_HOME "**%USERPROFILE%\AppData\Local\Android\Sdk**"
```
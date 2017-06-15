# 安裝 fish shell for macOS

先安裝Homebrew plugin 

```
➤ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
``` 

### 安裝 fish shell 

[參考網址](https://hackercodex.com/guide/install-fish-shell-mac-ubuntu/)

使用brew 安裝 fish shell plugin 

That said, if you already use Homebrew (which I recommend) and have configured your environment as noted in the macOS Setup Guide, then you can install Fish as you would any other package:
```
➤ brew install fish
```

If you would prefer to install the latest bleeding-edge version of Fish via Homebrew, run the following instead of the above command:
```
➤ brew install --HEAD fish
```

/etc/shells 增加 fish shell  plugin 相關參數

```
➤ echo "/usr/local/bin/fish" | sudo tee -a /etc/shells
```

設定 fish 為終端機預設 shell 

```
➤ chsh -s /usr/local/bin/fish
```

設定終端機版面樣式

```
➤ fish_config
```
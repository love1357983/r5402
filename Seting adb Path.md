# 設定 Android adb Path for macOS

### Step1.

```bash
➤ touch ~/.bash_profile
```

### Step2.

```bash
➤ vim ~/.bash_profile
```

### Step3.

```bash
# example
export PATH=$PATH:/Users/kuo/Library/Android/sdk/platform-tools
```

### Step4.

```bash
➤ source ~/.bash_profile
```

 這樣作完後就可以使用 adb command-line
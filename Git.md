## git 指令內容

```bash
➤ git
```

### 內容如下

```bash
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]
```
### These are common Git commands used in various situations:


```bash

# 啟動一個工作區域

start a working area (see also: git help tutorial)
   # 將網路已有的連結下載下來
   clone      Clone a repository into a new directory
   # 將所在目錄下初始化
   init       Create an empty Git repository or reinitialize an existing one
```

```bash

# 工作區塊指令

work on the current change (see also: git help everyday)
   # 加入檔案
   add        Add file contents to the index
   # 移動檔案
   mv         Move or rename a file, a directory, or a symlink
   # 重新設定
   reset      Reset current HEAD to the specified state
   # 移除檔案
   rm         Remove files from the working tree and from the index
```

```bash

# 檢查歷史紀錄與當前狀態

examine the history and state (see also: git help revisions)
   # 標記使用 https://git-scm.com/book/zh-tw/v1/Git-%E5%B7%A5%E5%85%B7-%E4%BD%BF%E7%94%A8-Git-%E5%81%9A-Debug
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   # 顯示日誌訊息
   log        Show commit logs
   # 顯示日誌活動訊息
   show       Show various types of objects
   # 顯示日誌狀態
   status     Show the working tree status
```

```bash

# 

grow, mark and tweak your common history
   # 分支列表、新增、刪除
   branch     List, create, or delete branches
   # 切換分支 或 回朔工作區塊
   checkout   Switch branches or restore working tree files
   # 撰寫日誌
   commit     Record changes to the repository
   # 顯示提交，提交和工作樹之間的更改等
   diff       Show changes between commits, commit and working tree, etc
   # 合併分支
   merge      Join two or more development histories together
   # 重新申請在另一個基本提示之上
   rebase     Reapply commits on top of another base tip
   # 創建，列出，刪除或驗證使用GPG簽名的標籤對象
   tag        Create, list, delete or verify a tag object signed with GPG
```

```bash

collaborate (see also: git help workflows)
   # 遠端分支 https://git-scm.com/book/zh-tw/v1/Git-%E5%88%86%E6%94%AF-%E9%81%A0%E7%AB%AF%E5%88%86%E6%94%AF
   fetch      Download objects and refs from another repository
   # 下載最新版本下來做 merge
   pull       Fetch from and integrate with another repository or a local branch
   # 上傳最新工作日誌
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
```

# dotfiles

## zed settings
install zed

[official](https://zed.dev/docs/installation)

### windows
```
$gitZedDir = "C:\Users\user-name\Git\dotfiles\zed"
$windowsZedDir = "C:\Users\user-name\AppData\Roaming\Zed"

# シンボリックリンクを作成
New-Item -ItemType Junction -Path $windowsZedDir -Target $gitZedDir
```

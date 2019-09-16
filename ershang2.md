## 关于 Git 客户端介绍

## 安装

点击[链接](https://sourceforge.net/projects/gitextensions/)处，下载 Git Extensions。双击下载好的 `msi` 文件安装。

出现这个界面时：

- 若未安装过 Git，可选择下面的 Putty；
- 若已经使用过 Git，可以选择上面的 OpenSSH。

> 这里是选择密钥加密方式。我们的 GitHub 远程仓库也需要钥匙才能打开。你注册的 Github 账号只能证明你具有管理仓库的身份，钥匙需要认证后生成，保存在本地。

一路右键，直到出现设置界面；如果缺少软件配置合并比较工具 `kdiff3`，说明未安装此工具，有两个解决办法：

- 点击[这里](https://sourceforge.net/projects/kdiff3/files/安装合并比较工具；
- 进入此界面左边的“Git -> 设置”中 ，选择本地已经安装的其它合并比较工具。


## 使用

### 将远程仓库克隆到本地

在你想放的位置（我知道肯定是桌面）打开右键菜单，选择“GitExt Clone”，粘贴上仓库的地址，然后点击`克隆`饥即可。

克隆完成后，将提示按 <kbd>Esc<kbd> 或者 <kbd>Enter<kbd> 退出。

### 将本地更改上传

改完了总要传吧？先对本地仓库文件夹点击右键`右键菜单 -> GitExt Commit` 

如果你真的点了提交而不是提交并推送，需要再右键点击文件夹 `右键菜单 -> Git Extension -> Push` 

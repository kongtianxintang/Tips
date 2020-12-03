##github 上传权限问题 只针对github Permission denied (publickey)
- 核心问题是公钥匙不匹配
- cd ~/.ssh
- ssh-add xxxx

##github 上传权限问题
- 核心问题公钥不匹配
- 添加new ssh key
- 查看本机上是否有密钥
- 一般在.ssh文件夹下
- 复制xx.pub公钥（clip ^ xx.pub）

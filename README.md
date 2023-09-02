# ComputerBackUp
备份一下自己电脑上的东西，以免电脑崩了
# 其他事情
1. 顺带学习一下git的使用，将本地文件提交到github，将github上提交的东西拉去到本地。
1. add new something that can  this file was changed

# Git 笔记

## 使用步骤

1. 创建密钥

   ```ssh-keygen -t rsa -b 4096 -C "your_email@example.com"```

参数说明：

- `	-t rsa`：指定生成 RSA 密钥。
- `-b 4096`：指定密钥的位数，4096 位通常被视为安全。
- `-C "your_email@example.com"`：提供一个标签（注释），这里用于标识密钥的所有者。

2. 在github上或者giteee上添加SSH密钥识别身份
3. 与远程库关联`git remote add origin git@github.com:…`
4. 或者克隆远程库` git clone git@github.com:…`
5. 查看远程库 `git remote -v`
6. 删除远程库origin `git remote rm origin`
7. 远程库推送`git push origin master`

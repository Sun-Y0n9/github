## git 学习笔记

### 初始化 添加文件 提交到本地仓库

+ git init 在文件内初始化一个本地git仓库.
+ git add file 添加文件. 
+ git commit -m "msg" 将添加的文件提交到本地仓库

### 版本退回

+ git log 查看提交信息.
+ git log --pretty=oneline 将提交信息在一行显示.
+ 在Git中，用`HEAD`表示当前版本.
+ 上一个版本就是`HEAD^`
+ 上上一个版本就是`HEAD^^`.
+ 上100个版本 HEAD~100
+ 
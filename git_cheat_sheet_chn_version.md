# GIT CHEAT SHEET CHINESE VERSION

>Written by Liangliang_Develoer

`git init`

**新建**版本库。目录下会多一个.git文件夹。

`git add filename.extension`

将`filename.extension`文件加入**暂存区**。

`git commit -m "comment"`

将**暂存区**内容提交到**当前分支**。

`git status`

查看当前仓库**状态**。

`git reset --hard HEAD^`

返回上一个版本。

`git reset --hard HEAD^^`

返回上上一个版本。

`git reset --hard HEAD~n`

向上返回n个版本。

`git reset --hard (comment id)`

返回到版本号所在版本（不需要写全版本号，只需要写前几位）

`git reflog`

查看每一次记录的命令（查找版本号用）




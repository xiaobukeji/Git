## Git 技能学习

#### Git 安装

`sudo apt-get install git` 在Linux上安装Git

`git config -l` 或者 `git config --list` 列出所有配置

`git config --global <option>` 配置全局选项

 - `git config --global user.name "Ervin Hua"`
 - `git config --global user.email "yhua.lin@qq.com"`


#### 创建版本库

`git init` 初始化一个Git仓库

`git add <file>` 暂存文件

 - `git add README.md` 或者 `git add .` 

`git commit` 提交暂存文件到本地仓库

 - `git commit -m "add README.md file"`

#### 版本穿梭

`git status` 查看工作区状态

`git diff` 查看修改内容

 - `git diff README.md`
 
`git log` 显示提交日志

`git log --pretty=oneline` 一行显示提交日志

`HEAD` 表示当前版本， `HEAD^` 上一个版本， `HEAD^^` 上上一个版本， `HEAD~100` 往上100个版本

`git reset --hard HEAD^` 回退到上一个版本

`git reset --hard 5ec5b8e` 指定回到某个版本

`git reflog` 查看命令历史

#### 版本修改

`git diff HEAD -- README.md` 查看工作区和版本库最新版本的区别

`git checkout -- <file>` 丢弃工作区的修改

 - `git checkout -- README.md`

`git reset HEAD <file>` 撤销暂存区修改

 - `git reset HEAD README.md`

`git rm <file>` 从版本库删除文件

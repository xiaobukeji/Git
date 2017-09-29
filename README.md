## Git Skills Study

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

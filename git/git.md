### *创建*

#### 克隆一个已存在的仓库

> `git clone git@github.com:Cckes/learngit.git`

#### 创建一个新的本地仓库

> `git init`

### *本地的改变*

#### 列出工作目录中发生改变的文件

> `git status`

#### 列出暂存区文件的详细信息

> `git diff <file>`

#### 添加修改过的文件到暂存区以待提交

> `git add <file>`

#### 添加一批修改过的文件到暂存区以待提交

> `git add -p <file>`

#### 提交暂存区中的所有记录到工作区

> `git commit -a <file>`

#### 提交暂存区中的一个文件到工作区

> `git commit -a <file>`

#### 修改上一个提交时的内容（不要修改已经发布了的提交）

> `git commit —amend`

### *提交历史*

#### 显示所有的提交，从最新的开始

> `git log`

#### 显示某个文件的详细修改信息

> `git log -p <file>`

#### 谁在什么时候修改了这个文件的什么

> `git blame <file>`

### *分支和标签*

#### 列出所有已存在分支

> `git branch -av`

#### 选择当前的分支

> `git checkout <branch>`

#### 创建一个新的分支

> `git branch <new-branch>`

#### 基于远程分支创建一个新的本地分支

> `git checkout —track <remote/branch>`

#### 删除一个本地分支

> `git branch -d <branch>`

#### 给当前的提交加上一个标签

> `git tag <tag-name>`

### *更新和发布*


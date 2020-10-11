## 一、github 本地仓库基本运用

1、生成.git仓库

    在当前文件夹下运行 git init 生成的一个.git 目录

2、将需上传/已修改的文件提交的暂存区

    git add

3、描述不需要提交的代码

    .gitignore 在此文件里写入不需要提交的文件名。常见的还有.idea\.DS_store\.vscode\.node_modules

4、将修改完成的文件上传到本地仓库

    git commit -v 方便回顾改动内容并说明提交理由
    git commit -m 版本一（注：上传理由）

## 二、github常用命令
    
    git log 查看创建的拷贝、版本号
    git reflog 查看所有分支的操作记录

    git rest --hard xxx 回到xxx版本的代码（注：次此操作会使没有提交的代码自动消失，用前确保commit了）

    start 目录 在电脑上打开这个目录
    git status 查看文件状态

## 三、基于当前文件创建一个分支

    git branch x 创建一个x分支(基于当前快照)

    git checkout 切换分支（本地代码也会相应切换）

    git stash 通灵术（用于临时把文件藏起来，既不提交也不删除，用git stash pop弹出）

    git merge 合并两个分支（保留那个版本就在那个支线操作） 

    git branch -d x 删除分支x

    
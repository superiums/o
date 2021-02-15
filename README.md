# 本地仓库

git init
git add
git commit -m “$comment”
git status
git diff
git reset --hard HEAD^|commitID <file>

恢复到某个版本



恢复到最新的库版本 git reset HEAD <file>

git checkout – <file>

丢弃工作区更改



git reflog



# 远程仓库

关联

要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

首次推送

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

推送

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
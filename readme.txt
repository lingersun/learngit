Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.


git checkout -b dev


查看远程库信息，使用 git remote -v
从本地推送分支，使用git push origin branch-name，如果推送失败，先用git pull 抓取远程的新提交。
在本地创建和远程分支对应的分支，使用 git checkout -b branch-name origin/branch-name,本地和远程分支的名称最后一致。
建立本地分支和远程分支的关联，使用 git branch --set-upstream branch-name origin/branch-name

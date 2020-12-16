# First
# 软件工程过程作业提交文档
1、git显示全部分支  

git branch //显示本地分支  
git branch -a //显示远程分支  
2、git创建分支  

git branch 分支名  
3、切换分支  

git checkout 分支名  
git checkout -b 分支名 若分支不存在，则创建它 
4、删除分支  

git branch -d 分支名  
-d 当分支已经合并到主干后删除  
-D无论如何都删除分支  
5、合并分支  

git merge 分支名  
6、撤销前一次commit  

git revert HEAD  
7、撤销所有本地修改  

git reset --hard  
8、撤销所有本地到上一次修改  

git reset --hard HEAD^  
9、撤销上一次commit，将commit的文件撤回暂存区  

git reset --soft HEAD^  
要是想撤销到上上次，就是HEAD^^ ,以此类推。  
git revert 是撤销某次操作，此次操作之前的commit都会被保留  
git reset 是撤销某次提交，但是此次之后的修改都会被退回到暂存区  
10、将此次更新文件并入到上次commit的记录中，不新添加commit  

git commit -amend  https://github.com/a280029097/test

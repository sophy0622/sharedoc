### Notes of Git

* git分支：  
1.新建本地分支： git branch <branch_name>  
2.新建远程分支： git checkout -b <branch_name> + git push (把新建的branch推送到远程服务器上)  
3.删除本地分支： git branch -d <branch_name>  
4.删除远程分支： git push origin :<branch_name> (把一个空的分支赋值给要删除的远程分支)
### 要关联一个远程库，使用命令
```
git remote add origin master git@server-name:path/repo-name.git
```
### 关联后，使用下面命令来完成第一次推送master分支的所有内容
```
git push -u origin master
```
### 此后，每次本地提交后，只要有必要，就可以使用命令推送最新修改
```
git push origin master
```




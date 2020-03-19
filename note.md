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
### Git鼓励大量使用分支:
  * 查看分支:
```
git branch
```
  * 创建分支:
```
git branch <name>
```
  * 切换分支:
```
git checkout  <name> or git switch <name>
```
  * 创建+切换分支:
```
git checkout -b <name> or git switch -c <name>
```
  * 合并某分支到当前分支:
```
git merge <name>
```
  * 删除分支:
```
git branch -d <name>
```



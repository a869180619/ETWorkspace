ETWorkspace
===========
##工程使用文档##
首先需要你有自己的账号，
确认你已安装git
下载工作空间 
``` 
git clone 网站 
```
 这时候这个模块的文件中内容是空的
```
git submodule update --init 
```
这个时候模块才会有内容
添加操作
```
git add .
```
看你有没有修改的部分
```
git status
```
查看分支
```
git branch
```
关于颜色说明:
master的颜色为红色表示你的版本低与他人，蓝色代表版本一致，
绿色代表版本高于他人。
当你想要新增加功能，首先要新创建一个分支
1.保存
2.commit
3.push to UpStream
4.分支完成，并且是一个稳定版本后需要添加到主干上
5.pull request（要求他人跟新功能）

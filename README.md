ETWorkspace
===========
##工程使用说明文档##
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
看你有没有修改的部分
```
git status
```
添加操作，当你有修改的时候使用，使得你的版本升高
```
git add .
```
查看分支
```
git branch
```
提交到本地
```
git commit
```
创建分支
```
git branch 分支名称 
```
删除分支
```
git branch --delete 分支名称
```

提交到主干上
```
git merge
```
提交到服务器上
```
git pull
```
request pull(要求他人跟新你的功能)   

关于颜色说明:   

master的颜色为红色表示你的版本低，蓝色代表版本一致，
绿色代表版本高于。    
      
readme使用
1.保存
2.commit
3.push to UpStream
ETWorkspace
===========
##工程使用说明文档##
首先chekout时候不需要注册账号，提交上去时候需要注册账号。   

确认你已安装git
在cmd命令中，下载工作空间
```
git clone https://github.com/a869180619/ETWorkspace/tree/Document
```
 这时候这个模块的文件中内容是空的，需执行
```
git submodule update --init 
```
这个时候模块才会有内容   。

看你的修改的部分
```
git status
```
提交所有的文件，同时也可以提交其中部分文件
```
git add .
```
查看
```
git branch
```
下载你所需要的库
```
git checkout 名称
```
当你修改的时候，先提交到本地，在向上提交
```
git commit   // 提交本地
```
向上提交
```
git pull
```
如果你想为工作空间新增功能的时候，首先创建分支
```
git branch 分支名称 
```
删除分支
```
git branch --delete 分支名称
```
当你的分支完场，切稳定的时候，合到主干上
```
git merge
```
最后提交到服务器上
```
git pull
```
pull request(要求他人更新你的新增功能)    

关于颜色说明:   

master的颜色为红色表示你的版本低，蓝色代表版本一致，
绿色代表你的版本高。    
      
readme使用
1.保存
2.commit
3.push to UpStream
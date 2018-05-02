# git-use
[English Readme](https://github.com/lixilin123/git-use/tree/master)
### 1.简介
本仓库介绍了使用git前需要做的一些事情
### 2.流程
1. 下载好git，安装好，并进行如下配置：
``` bash
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```		
2. 检查自己电脑上是否有私钥和公钥，没有的话使用如下命令创建：
``` bash
$ ssh-keygen -t rsa -C "youremail@example.com"
```
3. 将公钥内容拷贝到Github的SSH keys中;
4. 在本地创建一个目录并进入，然后使用如下命令拉取代码：
``` bash
git clone git@github.com:xxx/xxx.git
```
> 注意：以上地址是你要拉取代码的仓库的地址

5. 进入拉取好的仓库中，创建自己的分支，进行开发，将开发好的分支代码合并到测试分支(develop)或者主分支(master)上;

#Git-use

##### 第一步，下载好git，安装好，并进行如下配置：
	$ git config --global user.name "Your Name"
	$ git config --global user.email "email@example.com"
		
##### 第二步，检查自己电脑上是否有私钥和公钥，没有的话使用如下命令创建：
	$ ssh-keygen -t rsa -C "youremail@example.com"
		
##### 第三步，将公钥内容拷贝到Github的SSH keys中;

##### 第四步，在本地创建一个目录并进入，然后使用如下命令拉取代码：
	git clone git@github.com:xxx/xxx.git
	(以上地址是你要拉取代码的仓库的地址)
		
##### 第五步，进入拉取好的仓库中，创建自己的分支，进行开发，将开发好的分支代码合并到测试分支(develop)或者主分支(master)上

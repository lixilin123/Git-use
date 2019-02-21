# git-guide
> [中文文档](https://github.com/lixilin123/git-use/blob/master/README-zh.md)
### 1 Introduction
This is a github repository that describes some of the things you need to do before using git.
### 2. Process
1. Download git, install it, and configure it as follows:
``` bash
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```
2. Check your computer for private and public keys. If not, use the following command to create:
``` bash
$ ssh-keygen -t rsa -C "youremail@example.com"
```
3. Copy the contents of the public key to Github's SSH keys;
4. Create a directory locally and enter it, then use the following command to pull the code:
``` bash
Git clone git@github.com:xxx/xxx.git
```
> Note: The above address is the address of the repository where you want to pull the code

5. After the pull is completed, enter the local github repository, create your own branch, develop, and merge the developed branch code into the test branch (develop) or the master branch (master);

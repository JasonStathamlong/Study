Centos7 下安装及使用git

####1.安装及配置git
###1.下载安装git工具
root用户下执行命令：yum install git
安装完成可以使用命令：git --version查看版本信息
>git --version
git version 1.8.3.1

2.配置Git用户信息
$ git config --global user.name  “longzx” --你的GIthub用户名
$ git config --global user.email  “longzx@163.com”--你的GitHub邮箱
用户名和邮箱填写你github用户的
可以使用git config --list 查看配置信息

3.获取ssh key
$ ssh-keygen -t rsa -C “longzx@163.com” --你的邮箱地址

一直回车，最后他会提示你密钥放到哪个文件下了，打开那个文件复制里面的key

4.回到github用户界面，找到Settings进入以下界面

找到SSH and GPG keys 在右上角有个New SSH key 将复制的密钥添加上即可

2.git常用的功能
 1.

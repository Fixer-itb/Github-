# HW盖军雄Github学习报告
**学习于博客+廖雪峰**

。。。。。。。。。写完发现这可能不是报告。。。。。。。。

[toc]

## 知己知彼

 **GitHub**

 1.Github是基于git的代码托管，可以免费使用，快速稳定。

 2.利用GitHub，我们可以将项目存档，与他人合作，分享，交流，最大的优点是它支持多人

 共同完成一个项目。

 3.Too much...

### 正文开始

 **大纲**

[1.安装Git](#1.安装Git)

[2.了解主页，并创建第一个GitHub repository（仓库）](#2.了解主页，并创建第一个GitHub repository（仓库）)

[3.为GitHub账户设置SSH key：过程是这样，没敢整](#3.为GitHub账户设置SSH key：过程是这样，没敢整)

[4.上传本地项目到GitHub](#4.上传本地项目到GitHub)

## 1.安装Git

略

## 2.了解主页，并创建第一个GitHub repository（仓库）

 2.1：GitHub有三个主页：

 1.GitHub主页

 2.仓库主页

 3.个人主页

 2.2：创建仓库

 - 进入个人主页--->new--->依次填写 Repository name; Description (optional) --->

 顺便生成一个README--->Create repository.

 2.3：git命令

 创建Git仓库（在文件夹内初始化Git） `cd demo1` `git init`

 创建文件 `touch a1.c`

 将文件提交到暂存区 `git add a1.c`

 提交操作 `git commit -m"提交描述"`

 关联远程仓库

 `git remote add origin git@github.com:Fixer/esp.git`

 本地库推送到远程库

 `git push -u origin master`

 删除文件 `rm a1.php`

 从Git中删除 `git rm a1.php`



## 3.为GitHub账户设置SSH key：过程是这样，没敢整

 3.1：ssh key是加密传输

 1.生成ssh key

 if（检查是否生成了密钥：cd ~/.ssh--->ls）

 {

 如果有三个文件就已经生成

 id——rsa.pub 就是

 }

 else

 {

 通过$ ssh-keygen -t rsa -C "e-mail"来生成

 回车回车回车

 }

 2.生成成功后，去对应目录打开id_rsa.pub,得到了公钥

 3.2：为GitHub账号配置ssh

 个人头像小三角--->settings--->SSH keys--->Add SSH key--->下方key处黏贴

 配置完成

## 4.上传本地项目到GitHub

 4.1：你的工程文件（夹）

 4.2：建立本地仓库

 4.3：依次执行2.3的前七条指令



## Summary:总结:可用GitHub托管项目代码，可与他人方便快捷交流，且方便修改项目代码，总之还有很多功能待我学习@Richtung812

# Git使用说明

1.首先在git安装目录下找到并打开git-bash，设置基本信息：

```
git config --global user.name "You Name"
git config --global user.email yourmail@server.com
```

2.切换目录到你要提交的文件所在目录，输入git init初始化一个本地仓库。

```
git init
```

3.输入git add 要提交文件夹的名称 ，将文件添加到跟踪列表

```
git add [file1] [file2]
```

4.输入git commit -m "提交信息" ，将文件提交到本地仓库，提交信息必须填写

5.输入git remote add origin github代码仓库的url地址，将代码仓库与github关联

6.输入git pull origin master，将远程代码仓库拉回到本地，第一次提交可以不加，但以后提交时要加，否则代码可能会杂糅在一起。

7.输入git push -u origin master，将代码提交到github，输入回车后需要输入你的github名称和密码。
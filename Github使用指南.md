# Github使用指南

## Git的导入

### 安装

- linux中安装git的命令

```console
$ sudo apt-get install git
```

### 初始设置

- 设置姓名和邮箱地址

```
$ git config --global user.name "Firstname Lastname"

$ git config --global user.email "your_email@example.com"
```

- 提高命令输出的可读性

```
$ git config --global color.ui auto
```

## 使用Github的前期准备

- 创建账户
- 创建SSH Key

```
$ ssh-keygen -t rsa -C "your_email@example.com"
```

- 添加公开密钥

Account->Settings->SSH keys->New SSH Key

填写titile和key

- 查看Key命令:

```
$ cat ~/.ssh/id_rsa.pub
```

- 连接仓库

```
$ git clone git@github.com:heyaorui/hello-world.git
$ cd hello-world
```

- 常用Git命令

```
git status //查看状态
git add    //加入暂存区
git commit -m "提交说明" //提交
git log    //查看提交日志
git push   //更新Github仓库
```

## 基本操作


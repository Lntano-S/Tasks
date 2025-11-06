# 一、Github 注册

## 自主探索遇到的问题

填好个人信息后，一直卡在人机验证环节。在我询问大模型和在b站上学习相关视频后，发现是我的**网络问题**。随后我向朋友求助，借助“魔法手段”挂上代理后，我顺利地完成了 Github 的注册，进入到我的个人主页

# 二、创建自己的 Repo

## 1. 在 VScode 中配置 Git 的全局用户名和邮箱

在终端界面:

``` Git
git config --global user.name "Lntano-S"
git config --global user.email "1932474243@qq.com"
```

## 2. 在新窗口创建 Tasks 文件夹作为我的 Repo

首先创建 README.md 文件，随后在源代码管理界面，将我的修改commit到我的远程仓库，再发送消息提交，以同步到我的 Github 当中。至此，我的 Repo 创建完成。

# 三、和他人合作项目：Fork 和 Pull Request

## 1. Fork 他人的仓库

Fork 的本义为“叉子”，即从原仓库复制一个当前状态的到我的仓库当中，我可以对该 Repo 中的文件进行修改，但不影响原仓库，除非我提交 Pull Request。

## 2. 提交 Pull Request

在 Fork 来的 Repo 界面点击 Pull Request，并说明修改原因，以便原作者进行了解，提交之后，Pull request 请求就会发送至原仓库的作者。而如果原作者合并了我的修改，我将成为该 Repo 的 Contributors 之一。
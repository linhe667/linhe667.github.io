<head>
<title>my own web</title>
</head>
<body>
  <h1>Chinese poetry is swsome<h1>
  
第一个博客是看教程完成的
安装git
官方地址：https://git-scm.com/
对应访问git官方地址，下载的安装包，进行安装（简单的点击下一步）。
安装好之后，鼠标可以看到：Git Bash Here，点击后打开了。
输入：git --version
安装node.js
官方地址：https://nodejs.org/en/download/
对应访问nodejs官方地址，下载的安装包，进行安装（简单的点击下一步）。
安装好之后，配置环境变量，并在终端里面输入：node -v
安装 Hexo
安装命令：npm install hexo -g
测试是否安装成功，命令：hexo -v
安装hexo依赖
命令：npm install --save hexo-deployer-git
可以免密的将本地的源码和资源上传到github，无需每次都输入账号和密码。
先看本地是否配置好SSH密钥（命令：cd ~/.ssh）
配置ssh
先生成ssh密钥
ssh-keygen -t rsa -C "邮件地址"
备注：这里的邮件地址是github账号绑定的邮件地址
输入生成命令：ssh-keygen -t rsa -C "邮件地址"后。
可以看到在用户文件夹下生成了一个ssh文件夹
将id_rsa.pub复制的内容粘贴到key中，title轻松起一个就行。
点击添加SSH密钥
测试是否成功：
ssh -T git@github.com
输入测试命令后，接着输入是
配置账号和密码
$ git config --global user.name "xxx" #你的github用户名
$ git config --global user.email "xxx@163.com" #填写你的github注册邮箱
</body>

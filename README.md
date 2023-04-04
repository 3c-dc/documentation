# documentation
项目文档仓库

## 1.初始化项目文档仓库

添加READEME文档

## 2.基本的Git命令

<img src="https://github.com/3c-dc/documentation/blob/main/assets/git%E5%91%BD%E4%BB%A4.png" alt="git命令" />


```bash
# 基础操作:

	1. git  init 					# 项目初始化;

	2. git  add  .					# 所有文件添加到暂存区;

	3. git  commit  -m  "XXXX"			# 暂存区文件添加到本地仓库;

	4. git  status  -s				# 查看所有文件状态;

	5. git  log/reflog 				# 查看提交日历;

	6. git  reset  --hard  ID			# 版本切换;


# 分支操作:

	1. git  branch 					# 查看分支(主分支要提交一次)；

	2. git  branch  XXX				# 创建分支(根据主分支创建);

	3. git  checkout  XXX				# 切换分支;

	4. git  checkout  -b  XXX			# 创建并切换分支;

	# 5. 注意: 分支代码提交之后才能切换; 合并代码是站在主分支上，合并功能分支;

	6. git  merge  XXX				# 主分支合并功能分支;


# 远程仓库:

	# 1. 介绍: 本地仓库提交; 远程仓库创建(开源仓库，不要选默认添加文件);

	# 2. 介绍: https提交，ssh提交；ssh更安全，配置起来比较麻烦;

	3. git  remot  add  origin   https/ssh地址

	4. git  push  -u  origin  master

	5. git  remote  -v      		# 查询变量中存储的地址

	6. git  remote  rm  origin  		# 删除变量


# 多人协作开发:

	1. git  clone  SSH/HTTPS地址		# 克隆仓库

	2. git  pull  origin  分支名称		# 拉取远程仓库分支里面最新的代码

	3. git  remote  show  origin 		# 查看远程仓库分支

	4. git  checkout  # 远程分支 		跟踪分支(主分支拉，跟踪分支拉取在切换)

	5. 	.gitignore # 这个文件，可以忽略文件和文件夹，脱离git的管理;
	
```



## 3.基本的Node命令

```javascript
// node  app.js     // 执行js文件， 不要使用 npm   
// nodemon app.js   // 保存后重新启动

// npm init -y          初始化项目
// npm i nodemon -g     安装全局包(多出一个命令)
// npm i express@4.17.1
// npm i                安装所有包

// node包结构，package.json 中各属性，node_modules等

// .gitignore           git忽略哪些文件的管理
// git基础命令: 初始化，暂存，提交，远程推送，克隆...

// promise + async + await 

// es6 模块化， import   export

```



## 4.大事件项目文档

<img src="assets\01-大事件.png" alt="01-大事件" />

## 5.人力资源项目文档

<img src="assets\02-人力资源.png" alt="02-人力资源" style="zoom:60%;" />

## 6.头条项目文档

![03头条]("assets\03-头条.png")

# 最适合小白入门github教程

## 1.创建新仓库
### 1.1 创建仓库

### 1.2 获取上传权限的密钥
 	name: successfulbarrier
 	key: djkalsfjdklasjflsdjfksdflsfksldf
 	
### 1.3 创建本地仓库，并进行初次上传
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/xxx/xxxxx.git
	git push -u origin main
	
### 1.4 更新本地项目
	git pull	# 更新当前分支
	
## 2.使用或修改他人仓库

### 2.1 fork他人仓库

### 2.2 克隆到本地
	git clone --depth 1 https://github.com/xxx/xxxxx.git
	
### 2.3 查看分支
	git branch		# 查看本地分支，*指向当前所在分支
	git branch -r 	# 查看远端分支

### 2.4 创建分支
	git branch [branch name]	# 从当前分支拷贝，创建新分支
	
### 2.5 上传提交新分支
	git add .
	git commit -m "xxxxx"
	git push -u origin xxx
	
### 2.6 向远端提交pr
	
	
### 2.7 切换分支
	git checkout [branch name]	# 切换分支
	
### 2.8 和入xxx分支
	git merge xxx
	
### 2.9 查看历史版本
	git log
	
### 2.10 从历史本版创建新分支
	git checkout -b [new-branch] [commit id]	# 从某个历史版本创建新分支，并切换	
	
### 2.11 直接退回历史版本
	git revert -n [commit id]
	
	


git使用
##1,初始化 git init
##2,设置用户
   git config --global user.name "Nemo"
   git config --global user.email "Nemo@sina.cn"

##3,备份文件
  ###3.1拿到git中 
      git add ./readme.md 
 ### 3.2提交文件 (声明)
      git commit -m "完成了第一次提交"
# //第二次 提交
##1,拿到文件
## git add ./readme.md
## ##2,git commit -m "完成第二次提交"

 //第三次提交 未完成
## 4,判断当前状态
  git status  (红色 modefied,工作区未同步,绿色modefied,库版本未提交)
# 同时更新多个文件
 git add ./
 git commit -m
# 直接提交
git commit --all -m "这是一次性的操作"
## 查看日志
 - 'git log' 查看历史提交的日志
 - 'git log --online' 查看简洁版日志
## 恢复之前提交代码
 - git reset --hard Head~0
## 通过版本号切换
 -'git reset --hard'[ 版本号]
# 分支开发
- 创建分支
 +git branch dev
 +git branch 查看分支
 +git checkout dev 选择dev分支开发
-合并分支
 git marge dev	
-删除分支
 * 'git branch -d dev'
# https提交方式
#上传到服务器GitHub
 ## git push [github上传网址] master
#从服务器上下载
 *'git pull [https://github.com/NomeLouie/test.git]' master
#clone模式
git clone [网址] Clone 
## ssh方式上传代码
-公钥 私钥 两者之间是有关联的
-生成公钥和私钥
	+找到生成的公钥,提交GitHub上
	+ 'git push git@github.com:NomeLouie/testSSH.git mster'	
	+下载操作 'git pull git@github.com:NomeLouie/testSSH.git master'
## 解决冲突 
 - 先pull到本地,在本地解决冲突之后,在push提交
 - pull和push 上传下载代码的简写方式
 -push和pull 的-u参数操作,加上-u参数操作,那么下一次push/pull时,直接书写'git push'即可
# 正确使用md格式文件

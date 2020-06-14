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
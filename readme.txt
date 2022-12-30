首次提交，测试使用命令行上传代码

 1.git config --global user.name "ymyy32"
 2.git config --global user.email "18335108052@163.com"
 3.git init //初始化了一个本地仓库
 4.在终端中添加文件到远程仓库, 设置一个ignore文件忽略掉不需要上传的文件
 5.git add .
 6.git commit -m "first commit"
 7.git remote add origin https://github.com/ymyy32/test2.git
 8.git push -u origin master
 //发生错误 git pull --rebase origin master
//远程库与本地库不一致造成的，该命令的意思是把远程库中的更新合并到（pull=fetch+merge）
//本地库中，–-rebase的作用是取消掉本地库中刚刚的commit，并把他们接到更新后的版本库之中。
 提交完成
 测试修改提交
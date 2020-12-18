# shiyanlou-code
Shiyanlou_pratice
1.登录GITHUB创建远程仓库
2.克隆仓库到本地 git clone 仓库链接
3.或者创建本地空仓库 git init(这是 Git 的初始化操作，作用是将一个已存在文件夹，置于 Git 的控制管理之下)

基本流程：
Git 提交代码的基本流程是这样的：
创建或修改 本地文件
使用 git add + 文件名/目录名 命令，将创建或修改的文件添加到本地的 暂存区，这里保存的是你的临时更改

在提交之前，你必须先设置你的名字和 email，这是你在提交 commit 时的签名，每次提交记录里都会包含这些信息。
git config --global user.name "YourName"
git config --global user.email "YourEmail@xxx.com"

使用 git commit -m "注释" 命令，注释为 “first commit” 的，提交文件到 本地仓库

git remote add 仓库小名 仓库链接
fatal: 远程 origin 已经存在。
此时只需要将远程配置删除，重新添加即可；
git remote rm origin（小名）

使用 git push origin master 命令，将本地代码库同步到 远端仓库（需要输入账号密码）
输入 git status ，可以检测当前目录和暂存区的状态，查看哪些修改被暂存了



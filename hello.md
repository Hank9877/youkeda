2.4 绑定远程仓库

2.4.1 初始化git仓库：用git init将一个文件夹初始化为一个git仓库

2.4.2 绑定本地仓库：

git remote -v：查看当前git仓库绑定的远程仓库，显示空白即无绑定。

git remote add origin 仓库地址 （git@github.com:qq953366045/youkeda.git）

绑定成功后用git remote -v可以查看是否绑定成功。

绑定错误可以用git remote remove origin来移除绑定
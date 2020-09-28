绑定本地仓库到github
1.在github创建一个同名的空仓库
2.本地已有同名文件夹，用cd命令进入
3.初始化为git仓  git init



4.绑定远程仓库 git remote -v()查看当前git仓绑定的远程仓库  刚初始化的的仓库一般是没有远程绑定的，而从线上clone下来的仓库必然是有远程仓库的

【若使用remote命令显示是空白既无绑定】

git remote add origin 仓库地址

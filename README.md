git上传代码到github操作
1、安装git，网上查看
2、上传代码
1）本地操作-切到源码目录，git init
2）添加到本地仓库：git add --all
3）可用git status查看
4）git commit  -m  "提交信息”
5）复制你的仓库SSH链接，比如 git@github.com:flyonaie/mycyberRT.git
6）这里是你需要推送仓库链接 的命令
git remote add origin git@github.com:ueshk/ithuc.git
//例如我的是：git remote add origin git@github.com:flyonaie/mycyberRT.git
7）把本地仓库代码推送到远程仓库
git push -u origin master


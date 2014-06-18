本人使用opensuse系统

git是早就安装好的

可以用以下命令安装

`sudo zypper install git`

然后去 https://github.com/zwz 把git-test这个项目Fork一下，这是你自己的repositories里就已经有了这个项目的fork了。

一般把项目clone到本地进行修改，在终端使用以下命令、

`git clone https://github.com/Chihell/git-test.git`

进入工作目录

`cd ./git-test`

这是就可以增加或修改文件了,比如我增加了一个文件

`vim ./Chihell-戚加欣.md`

完成后使用一下命令把文件加入本地缓存区

`git add Chihell-戚加欣.md`

然后commit进本地仓库，注意填写良好的提交信息

`git commit -m "add Chihell-戚加欣.md"`

本地仓库完成后就可以push到远程仓库了

`git push`

这时登录你的GitHub可以发现你的repositories中已经出现你的修改结果了。

如果你想对你fork的项目提交你自己的修改，可以对原repositories的拥有者发出pull request

点击compare,review,create a pull request按钮，就可以给他发pull request啦。 `-_-`

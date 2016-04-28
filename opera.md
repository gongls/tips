将下列信息添加到你的 apt sources.list（/etc/apt/sources.list） 文件：

deb http://deb.opera.com/opera/ stable non-free

如果提示无法验证，可以这样来安装key：

wget -O - http://deb.opera.com/archive.key | sudo apt-key add -

或者，你需要最新的beta版本：

deb http://deb.opera.com/opera-beta/ stable non-free

.修改后保存 sources.list 文件，然后在终端中输入：

sudo apt-get update

接下来：

sudo apt-get install opera

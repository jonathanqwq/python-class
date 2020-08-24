# 现邀您加入python教程编写团队!

> 现邀您加入python教程编写团队!

该项目由我发起，致力于给没有python编写经验的人们编写教程，供国内需要学习python教程的开发者学习参考。  
由于项目较为庞大，希望志同道合的朋友们和我们一起努力。  
加入方法请见下方。

第一种加入方法：（推荐）
由于本项目使用github进行代码托管和版本管理，您需要使用git工具来和我们保持同步。  
如果您没有安装Git客户端，请前往git官网下载并安装官方Git客户端。  
如果您没有github账号，请前往github官网 注册一个。

请您给我发送一封Email(2841306779@qq.com)，其中注明您的github账号名。  
我在阅读后会给您回信并在github上发送合作申请，请注意查收。  
在等待结果时可以继续下面的步骤。

找一个位置方便的文件夹用来保存网站的所有文件。您将在这里离线开工。  
文件夹不一定要是空的，因为数据会存在子文件夹里。

进入这个文件夹，打开右键菜单并选择Git Bash Here。  
将弹出一个命令行窗口。等待程序初始化完成，在窗口中打出一行以 $ 结尾的文字时，输入以下指令。  
每条指令复制粘贴更改后回车。  
```git clone https://github.com/jonathanqwq/python-class.git```
由于数据量较大，请稍等一会儿。可能需要一段时间。

完成后，执行```git remote -v```，确认回显文字。如果自动添加正常的话，应当显示如此：  
```origin https://github.com/jonathanqwq/python-class.git (fetch)```  
```origin https://github.com/jonathanqwq/python-class.git (push)```  
如果没有显示，则需要手动添加远程站点。执行以下指令。  
```git remote add origin https://github.com/jonathanqwq/python-class.git```  
```git init```  
完成之后再次执行```git remote -v```，此时应当出现正常的远程站点信息显示。

好的，设定完成。已与远程代码库建立联系。

接下来输入以下两条指令。每条指令复制粘贴更改后回车。  
```git config --global user.email "更换为您注册的Email，不要去掉引号"```  
```git config --global user.name "更换为您注册的用户名，不要去掉引号"```  

进入python-class文件夹，打开右键菜单并选择Git GUI Here。  
为方便我们之后的操作，请选择顶部菜单中的Tools -> Add，并在对话框中填写如下内容。Name一栏可随便。之后点击Add。  
选择顶部菜单中的Edit -> Options，并点击图示的两个按钮，在弹出的下拉框中选择Unicode (UTF8)。这会解决中文乱码的问题。

用您偏好的网页编辑软件直接开始修改即可。不需联网。  
在编辑时请注意保存为不带BOM的UTF-8文字编码格式。 

请注意，此教程使用docsify编写，您需要先去 https://docsify.js.org/#/zh-cn/ 了解docsify。
在使用```npm i docsify-cli -g```时，请先安装node.js。
 
您必须接受合作邀请之后才可以上传。如果还没有收到请稍等。  
编写完成后进入python-class文件夹，打开右键菜单并选择Git GUI Here。  


如图，首先点击Rescan搜索改动文件，可以看到改动过的文件出现在左上角。然后点击State Changed标记更改状态，可以看到它们移动到左下角。接下来在大文本框里写一行提交信息（即你干了什么，动词直接开头，不加“了”等过去式词语），之后点击Commit提交更改，Push上传更改。  
在点击Push时会跳出push branches对话框,不管他，再次点击右下角push。
可能会让你登录github,直接登陆即可。

有时点击Push时候会失败，并弹出一个对话框，里面含有fast-forward字样。  
这是因为在您上次提交之后至这次提交之前，其他成员也修改了在线文档，使得您本地的代码和在线的代码不同步了。遇到这个情况，点击Tools菜单中添加的列表项，即可拉取在线代码的更新到本地。然后您就可以再次点击Push了。

事实上，我们建议您每天开工前都执行一下拉取操作，来保持时刻同步。  
在最糟糕的情况下，点击拉取时也会报错，报出的错误中含有CONFLICT字样，这表明您和另一位“撞车”了——同时往不同方向翻译了同一篇文档。点击确定后，软件将自动显示出含有冲突的文档，以及两方不同修改方向的修改内容。
您可以比较这些内容，并且选择Use Remote Version（按照远程那边一版走），或者Use Local Version（按照自己本地一版走），或者打开文件手动修改，写成同时具有两版优点的一版，然后再选择Use Local Version。全部修改完之后，按Commit和Push修正错误。

因为网络原因，也可能出现一些其它的错误。对于其它的报错信息，可以重试几次。如果怎样都不行，请和其他成员联系解决。

为了尽量避免撞车，项目组使用邮箱进行任务分配。
未收到任务的成员请勿自行更改文档，否则将被移出编写组。

第二种加入方法：（可能出现问题）  
如果您没有安装Git客户端，请前往git官网下载并安装官方Git客户端。 
 如果您没有github账号，请前往github官网 注册一个。

请您给我发送一封Email(2841306779@qq.com)，其中注明您的github账号名。  
我在阅读后会给您回信并在github上发送合作申请，请注意查收。  
在等待结果时可以继续下面的步骤。

使用指南
本工具安装过程包括多个步骤，但并不特别复杂。

找一个位置方便的空文件夹用来保存网站的所有文件。您将在这里离线开工。  
新建文本文档，重命名为pagit.sh（注意后缀！），放入下方代码  
```pagit.sh 此工具由zbx1425编写，jonathanqwq修改。
#!/bin/bash

# 配置 / Configuration

# 您的Email / Your Email  
GIT_EMAIL="somebody@somewhere.com"

# 您的英文名 / Your Name  
GIT_UNAME="somebody"
 
HTTPS_PROVIDER="https://github.com/jonathanqwq/python-class.git"

# 您的github/gitee注册时使用的邮箱 / Your github/gitee Email address for registration  
HTTPS_USERNAME="somebody"

# 您的github/gitee密码 / Your github/gitee password  
HTTPS_PASSWORD="somebody"



COMMIT_MSG="使用pagit上传"  
HTTPS_USERNAME=$(echo $HTTPS_USERNAME | tr -d '\n' | xxd -plain | sed 's/\(..\)/%\1/g')  
HTTPS_PASSWORD=$(echo $HTTPS_PASSWORD | tr -d '\n' | xxd -plain | sed 's/\(..\)/%\1/g')  
HTTPS_PROVIDER=$(echo $HTTPS_PROVIDER | sed s#://#://$HTTPS_USERNAME:$HTTPS_PASSWORD@#)  
echo $HTTPS_PROVIDER  
if [ ! -d .git ]; then  
	git init  
	git config user.name $GIT_UNAME  
	git config user.email $GIT_EMAIL  
fi  
if [ -z $(git remote) ]; then  
	git remote add origin $HTTPS_PROVIDER  
fi  
pmg=$(git pull --set-upstream origin master 2>&1); pst=$?  
echo $pmg | grep "couldn't find remote ref master" >/dev/null; echo $pmg  
if [ $pst != 0 -a $? != 0 ]; then  
	echo -e "\033[31m 发生合并冲突. 请手动解决! \033[0m"  
	echo -e "\033[31m Merge conflict. Please resolve it manually! \033[0m"  
	exit  
fi  
grep "pagit.sh" .gitignore >/dev/null  
if [ $? != 0 ]; then echo "pagit.sh" >>.gitignore; fi  
git add .  
if git commit -m "$COMMIT_MSG"; then  
	git push origin master  
	echo -e "\033[32m 上传完成. 谢谢! \033[0m"  
	echo -e "\033[32m Commit succeed. Thank you! \033[0m"  
	if echo $HTTPS_PROVIDER | grep "gitee.com" >/dev/null; then  
		echo -e "\033[33m 上传完成.如果您使用此工具修改码云pages文件，请勿忘记在码云网站上手动更新Pages. \033[0m"  
		echo -e "\033[33m Upload completed. If you use this tool to modify the pages file, please do not forget to manually update pages on code cloud website \033[0m"  
	fi  
else  
	echo -e "\033[33m 没有文件变动. \033[0m"  
	echo -e "\033[33m No file was updated. \033[0m"  
fi  
if [ $# == 0 ]; then read -n 1; fi
```

关闭编辑界面，在文件夹中打开右键菜单，并选择Git Bash Here。  
将弹出一个命令行窗口。等待程序初始化完成，在窗口中打出一行以 $ 结尾的文字时，输入以下指令。  
每条指令复制粘贴更改后回车。  
```git clone https://github.com/jonathanqwq/python-class.git```

右键pagit.sh->"打开方式"，用你喜欢的编辑器打开这个文件(不要"始终使用")
请在收到邀请并同意后, 按照里面十分明了的指示填入配置项。

用您偏好的网页编辑软件直接开始修改即可。不需联网。  
在编辑时请注意保存为不带BOM的UTF-8文字编码格式。 

请注意，此教程使用docsify编写，您需要先去 https://docsify.js.org/#/zh-cn/ 了解docsify。
在使用```npm i docsify-cli -g```时，请先安装node.js。

修改完成后双击pagit.sh。它应当提示"没有文件变动"或者"提交完成"。
请在每次修改前输入```git clone https://github.com/jonathanqwq/python-class.git```。

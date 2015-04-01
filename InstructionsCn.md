# 5分钟DIY一个私房代理服务器（写给非CS专业人士) #

By memedarwin (http://vivachina-tata.blogspot.com/)

开始：

  1. [Sign up](http://appengine.google.com/) for an App Engine account. 先注册帐号，用GOOGLE帐号登陆后 "Create an Applicaton"，然后会要求用手机接收一个短信认证号。认证通过后，你需要给这个代理起个名字（以xxx为例），作为 identifier，以后可以通过 xxx.appspot.com 来访问。
  1. [Download](http://code.google.com/appengine/downloads.html) 下载 the App Engine SDK.
  1. Download and install 下载且安装 Python 2.5 for your platform from http://python.org/download
  1. Install 安装 the App Engine SDK.
  1. 在SDK安装目录下用注册的identifier新建文件夹xxx
  1. 下载mirrorrr（1) http://code.google.com/p/mirrorrr/source/browse/#svn/trunk 所有文件 下载到一个文件夹xxx（2）http://code.google.com/p/mirrorrr/source/browse/#svn/trunk/static%3Fstate%3Dclosed 所有文件下载到xxx的子文件夹static (需新建)为节省大家时间，我把所有源程序打包上传到http://rapidshare.com/files/193345202/mirror.rar，只要下载后解压到SDK的安装目录下的XXX就可以。
  1. 在XXX目录下有个文件app.yaml，用NOTEPAD打开，改写第一行 application: xxx,存盘。
  1. 运行CMD命令，进入SDK安装目录，appcfg.py update xxx , 输入GOOGLE帐号，再输入密码，如果回复：<br />Cloning 8 static files.<br />Cloning 6 application files.<br />Closing update. Uploading index definitions.<br />安装完毕！
  1. 测试，IE输入，HTTPS：//xxx.appspot.com , 恭喜你，DIY成功！
  1. 运气不好？我知道，给我回个贴，或许我能帮到你(http://vivachina-tata.blogspot.com/)！

感谢Bslatkin 的天才和智慧，让更多人轻而易举的获得自由！
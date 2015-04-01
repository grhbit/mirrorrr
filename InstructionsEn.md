How to build your personal web proxy in 5 minutes--a short tutorial for everyone

By memedarwin (http://vivachina-tata.blogspot.com/)

You use proxy because [reason here](your.md) and mirrorrr  can help you do that better.  The opensource program is written by Bslatkin  and run on Google's application platform "Google Appengine ". It is free, secure, fast and belongs to you after you build it. Here is a short tutorial for everyone interested but with no programming knowledge.

  1. [Sign up](http://appengine.google.com/) for an App Engine account. Then "Create an Application"，you will need a cellphone to validate your account. After validation, you will give your proxy a name (identifier)， which can be accessed via identifier.appspot.com. Here we use xxx as an example.
  1. [Download](http://code.google.com/appengine/downloads.html) the App Engine SDK
  1. Download and install Python 2.5.4 for your platform from the [Python website](http://python.org/download)
  1. Install the App Engine SDK.
  1. Create a folder named xxx in the Appengine SDK installation folder(e.g. C:\Program Files\Google\google\_appengine\).
  1. Download mirrorrr source files. There are two parts.（1) http://code.google.com/p/mirrorrr/source/browse/#svn/trunk  Download these files to your xxx folder; （2）http://code.google.com/p/mirrorrr/source/browse/#svn/trunk/static%3Fstate%3Dclosed Create a "static" folder in xxx and download these files to it;  To save you time, I have upload the two parts files to http://rapidshare.com/files/193345202/mirror.rar so you can download and unzip it to your xxx folder.
  1. Now edit app.yaml in the xxx folder with notepad or any editor，change some words in the first line to application: xxx. Save the file and exit.
  1. Type CMD in Start>run and enter command line environment. Enter your Appengine SDK folder(C:\Program Files\Google\google\_appengine\), type "appcfg.py update xxx ", you will be prompted to enter your account and password.  After validation the files in xxx folder will be uploaded to google and your installation is completed. You will receive the following message:<br />Cloning 8 static files.<br />Cloning 5 application files.<br />Closing update.<br />Uploading index definitions.<br />You are almost done!
  1. A test will be done by enter in your browser: https//xxx.appspot.com
  1. If you're having issues, let me know!

Acknowledgement:  Bslatkin's talent and wisdom has made people enter the free world with little effort.
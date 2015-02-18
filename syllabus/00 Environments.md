Environment Setup & Code Editor
===============

Setting up your local environment

These are instructions for setting up a local environment to build websites. If you set this up, you will have the ability to build and test your personal projects without needing internet access. 

Applications
In order to build a local environment quickly, I have selected the following applications to get you started. As you develop your skills, you may find other applications that fit your style. 

<a href='http://www.mamp.info/'>Install MAMP (basic version is fine, you don't need the pro version)</a> <br>
<a href='http://www.sublimetext.com/3'>Install SublimeText 3</a>


*** Create a folder for all your projects ***
Be sure to create a folder on your computer that will have all your projects in it. Be sure to account, not just for 1 single application, but for a number of projects. I would create the following folder structure to start:

"/desktop/development/project1/"

If you add more projects, add them all to the "development" folder. When you are done, you will have an organized folder structure like this...

/desktop<br>
&nbsp;&nbsp;&nbsp;/development<br>
&nbsp;&nbsp;&nbsp;&nbsp;/project1<br>
&nbsp;&nbsp;&nbsp;&nbsp;/project2<br>
&nbsp;&nbsp;&nbsp;&nbsp;/project3<br>
&nbsp;&nbsp;&nbsp;&nbsp;...<br>

*** Setting up MAMP, a free webserver ***
Run the installer. 
After successful installation you can launch your local servers. Start MAMP and click on the Start Servers button. In the status display in the upper right corner, the launch status of the servers is displayed. If necessary, you will be asked for your administrator
password.

![MAMP](/images/mamp-preferences.png) 

The web server (Apache) starts by default on port 8888, the database server (MySQL)
on port 8889. Be sure to change this by setting the web server to port 80 and the MySQL server to 3306. Some newer versions of MAMP also allow for NGNX configuration. If so, set that port to 81.

![HTML](/images/mamp-ports.png) 

Next, for the project you want to view in th browser, you have to point MAMP to the folder.
Click on to select where your html/PHP files and images are stored. This directory is called Document Root. The default Document Root in MAMP is:
/Applications/MAMP/htdocs but you should change this to /desktop/development/project1 to view project1 or /desktop/development/project2 to view project2, etc.

![HTML](/images/mamp-document-root.png)

That is it, once you have all these steps complete, you can pull up localhost/ on your computer and view the webpage in your project1 folder or whatever project you selected in the document root section above. 

*** Setting up Sublime ***
Once Sublime is installed read this Google Developer write up on using it. It also gives some handy plugins you can install with it. 

https://developers.google.com/web/fundamentals/tools/setup/editor?hl=en

When you are in sublime, first you need to create a project. The page will be empty. 

![HTML](/images/sublime-blank.png)

Go to Project > "Add Folder To Project" and open /desktop/development/project1. You will then see Sublime create a sidebar with that folder structure.

![HTML](/images/sublime-add-folder.png)

![HTML](/images/sublime-sidebar.png)



Then add your standard project folders into your project1 folder. I like to have folders for the files that could be in the project. 

/project1
	/css
	/js
	/img

Create your first file (index.html) in the root of the project1 folder and when you open a web browser and type localhost/ in the URL bar, that file will be displayed!





---
layout: post
category : lessons
title: PyCharm vs Spyder: a quick comparison of two Python IDEs
tagline: "Supporting tagline"
tags : [intro, beginner, jekyll, tutorial]
---
{% include JB/setup %}

In this post, PyCharm vs Spyder will be compared. If you have followed my blog you may have noticed that a lot of focus have been put on how to learn programming (particularly in Python). I have also written about Integrated Development Environments (IDEs). I think that an IDE may, in fact, be very useful when learning how to code. Of course, when it comes to Python IDEs it may be hard to choose the best one (e.g., PyCharm vs Spyder?)

Spyder is one of my long-time favorite IDEs, and I am mainly using Spyder when I have to write code in Windows environments. However, in one of my blog posts PyCharm was suggested in one comment (see the comments on this post: Why Spyder is the Best Python IDE for Science) that I should test PyCharm. .

After testing out PyCharm I started to like this IDE. In this post you will find my views on the two IDEs. E.g., I intend to answer the question; which is the best Python IDE; PyCharm or Spyder?

	

The post will divided into the following sections:

Shared features of PyCharm and Spyder
PyCharm
Spyder
PyCharm vs Spyder
In the first section (1) I will outline some shared features of PyCharm and Spyder. I will then continue with describing features that is unique to PyCharm (2) and Spyder (3). Finally, I will go on and compare the two Python IDEs (4).

Shared features of PyCharm and Spyder
I will start discussion some of the shared features of PyCharm and Spyder. First, the both IDEs are free (well, Spyder is “more” free compared to PyCharm but if you are a student or a researcher you can get the full version of PyCharm free, also) and cross-platform. This means that you can download and install both Spyder and PyCharm on your Windows, Linux, or OS-X machine. This is of course awesome! PyCharm and Spyder also have the possibility to create projects, an editor with syntax highlighting and introspection for code completion, and have support for plugins.

 

pycharm-best-ide-python

PyCharm
I must admit, the main thing I liked with PyCharm was that I could change the theme to a dark. I really prefer having my applications dark. That said, PyCharm of course comes with a bunch of features. I will not list all of them here but if you are interested you can read here. As I have mentioned earlier, both PyCharm and Spyder have support for plugins. However, I find it easier to find and install plugins in Pycharm. To install a plugin you just open up settings (File -> Settings) and click on “Plugins”:


PyCharm install plugins
 

This makes it very easy to search for plugins. For instance, one can install Markdown plugins to also write Markdown files (.md) that can be uploaded to your Github page. That leads me into another GREAT future of PyCharm; support for different types of Version Control Systems (VCS: e.g., GitHub, Subversion, and Mercurial). E.g., uploading your work to GitHub is only a few click aways (if you prefer not to use command line, that is).



Another great feature is that you can set the with of your code and PyCharm will end our line and move it to next line (great if you are a lazy programmer.)

Another feature of PyCharm is that you can safely rename and delete, extract your methods, among other things. It may be very helpful if you need to rename a variable that is used on various places in your code.

One of my favorite features is that you can, much like in RStudio for R, install Python packages from within the interface. PyCharm offers an easy system to browse, download, and update 3rd party packages. If you are not only working with Python projects, PyCharm allso provides supprot for Javascript, CoffeScript, Typescript and CSS, for instance.

Spyder

Spyder GUI
First of all, Spyder is made in for and in Python! Of course this is not a feature of the IDE itself but I like that it’s quite pure Python!

However, one of the most obvious pros with Spyder is that is much easier to install (e.g., in Ubuntu) compared to PyCharm. Whereas PyCharm must be downloaded and installed, Spyder can be installed using Pip. It is also part of many Linux distributions package manager (e.g., apt in Debian Ubuntu).  There is one thing, however, that I really like with the Spyder interface; the variable explorer.


Spyder variable explorer
In Spyder it is also quite easy to get help. That is, if you are getting stuck, and is not sure how to use a certain function or method. The help function of Spyder IDE lets youtype in the object and get the document string printed out. It can come in very handy, I think.


Spyder help/object explorer
Spyder vs Pycharm
It is easier to install Spyder (at least in Linux) but PyCharm is not that hard to install. In fact, if you are running Ubuntu you can just add a PPA (See here on how to install PyCharm this way) and install PyCharm using your favourite package manager. If you are a Windows user, you just download an installation file (Download PyCharm).

Spyder is also part of two great Python distributions, Anaconda and WinPython. Anaconda is cross-platform and WinPython for Windows only. Both distributions comes with most of the Python packages that you may need (and probably more than you need!)  Thus, you will get a lot of what you need to write code and Spyder in one installation.

PyCharms have support for VCS systems (e.g., Git and Mercurial) is also a great feature that is in favor for PyCharm. I know that some people find this attractive; they don’t have to use the command line.

Okey, which IDE do I think is the best? I think that Spyder, still, is a great IDE. PyCharm do, of course, offer a lot more features. If you are running a relatively new computer and is using Linux (e.g., Ubuntu), PyCharm may be the best (almost) free Python IDE.

On the other hand, if you are using Windows and don’t want to install a lot of Python packages by your self, Spyder you can choose to install either Anaconda or WinPython.

In fact, in the lab where we run Windows 10 computers, I have installed Anaconda (as can be read in the comments, Python(x, y) is no longer maintained). Here I use Spyder but at home I tend to write in PyCharm.

In conclusion, for scientific use maybe Spyder is the best free Python IDE (for Windows, Linux and OS-X). If you are a more general programmer or want to have a lot of features within the interface, PyCharm may be your choice!

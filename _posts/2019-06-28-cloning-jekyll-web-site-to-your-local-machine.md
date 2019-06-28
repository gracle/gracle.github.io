---
title: Cloning Jekyll blog to local directory
category: Jekyll
---

In previous articles, you might have read about creating a website using Jekyll, and setting up jekyll on your local machine. If not, please take a look at those articles.

In this article, we're going to clone our previously created website to our local machine to ensure easy development of our website. We can either clone it by using git or we can download a zip of our whole repository, then extract it to our work folder. But, in this tutorial we will use git to clone it.

We need the following to continue:

1. A working internet connection
2. git

Don't worry if you didn't install git on you machine. Simply follow the steps below.

Let's begin with the installation of git. If git is already installed in your system, you can skip those steps involved in git installation.

If you're a Windows user, just download git installer from <a target="_blank" href="https://git-scm.com/download/win">here</a>. Install it by double clicking.

If you are a Linux user, install git by using the following command:
	
		su
		apt-get install git

Done.

You got git installed on your machine. Now you can clone your repository where your site is hosted.

For that, go to GitHub and navigate to your repository. 

Click a green button "Clone or download". You'll get a link to clone your repo (ending with .git extension). Copy that link.

Open your terminal (Command prompt in Windows) and type the following command:
		
		cd <path to your work folder>
		git clone <the url we're copied>

Example:
		
		cd gracle
		git clone https://github.com/a4arjun/gracle-jekyll-template.git

Your website will be cloned as yourdomain.github.io inside your work folder.

Now you can start jekyll server on the directory:
		
		jekyll serve

Open your browser to see your cloned website.

In next article, you can read about adding posts to your jekyll blog and formatting markdown files. Thanks for reading.

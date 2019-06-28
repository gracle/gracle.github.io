---
title: Setting up Jekyll on a local machine
categories: Jekyll
tags: [markdown, ruby]
---

In the previous article, you've learned about creating a website with jekyll on GitHub. Now, we're going to install jekyll on our local machine and start develop blogs and websites locally. Let's begin.

Requirements

1. A computer with Ruby installed.
2. Internet connection
3. Lot of patience

For the installation of Jekyll, we need to have Ruby installed on our system. Ruby version should be greater than 2.4+.

You can check whether Ruby is installed on your system by using the following command:

		ruby -v

It will print the installed version. If not installed, you can install Ruby.

If you're a Windows user, simply go to Ruby's download page and download the latest installation package and install it by double clicking.

If you're a GNU/Linux user, open uour terminal. Enter the following commands (Don't need to enter 'su' if you're superuser already):

		su
		apt-get install update
		apt-get install ruby2.6

You're done.

(I'm using Debian. The above commands won't work in Fedora, Arch etc. But, will work with Debian derrivatives like Ubuntu)

Next, check the gem version by the following command.
		
		gem -v

Now, you can proceed to the installation of Jekyll. Install Jekyll using the following command:

		gem install jekyll bundle

After installation, check the version of Jekyll by using the command:

		jekyll -v

DONE!

NOw, we csn start creating our first website. For that , create a new work folder. You can give any name. In my case, I've named it "gracle".

Open your terminal pointing that directory.

Start the server by:

		jekyll serve

The server will be started soon. You will see the following screen after the server is started.

Now, go to your work folder. There you can see another directory called "_sites". This is the directory where you need to place your Jekyll pages (like www/public_html folders in apache/nginx etc.).

Create a new file named "index.html". Add the following code (Or you can add any code)

		<html>
		 <head>
		  <meta>
		  <title>My first Jekyll webpage</title>
		</head>
		 <body>
		  <h1> Hello Jekyll</h1>
		 </body>
		</html>

Open your webbrowser, enter the following url on your adress bar:

		http://localhost:4000/

Bingo! You can see the result as per the above code.

In the next article, we're going to learn in depth about Jekyll blogging


Thanks for reading.



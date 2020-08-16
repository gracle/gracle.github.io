---
title: Creating a post for your Jekyll blog
category: Jekyll
---

In this article, you can read about adding posts to your Jekyll blog. You have two options to add posts to your Jekyll blog. You can either create a post locally then upload it to your repo or create it directly on your github repo itself.

Here, we are going to prepare the post locally, and upload it to our repo. 

Before we start, we need to understand about posts. 

1. Our posts should be in a folder called "_posts" on the root of our website.

2. Name of the post should be in a format such that,
		
		YEAR-MONTH-DATE-POSTNAME.md

Where, year is the current year, month is the current number (ie, if June is the month, you must add 06) and the spaces in the post name should be replaced with '-' character. You can use either html or md(markdown) as file extesion.

Let's take an example. I'm creating a post on June 30, 2019. My post name is "Creating a post for my Jkyll blog"

I have to name it:
		
		2019-06-30-creating-a-post-for-my-jekyll-blog.md

Here I used .md file extension. Because md file is more readable than the html file. If html is more comfortable for you, go for it. Then we can add contents on it. 

Now, create a file in above format. You can use any of your favourite text editor. I'm using pluma as my text editor.  

Then, inside your md/html file, the structure should be as follows:
		
		---
		title: Creating a post for my jekyll blog
		category: Jekyll
		---
		
		Contents goes here. You can add pictures, format text etc.
		You can use html tags to format the content.

Done. It may confuse it for the first time. But, it's very simple to understand.

The data we added inside --- and --- is called "front matter"

title is the title for our post. Category is the post category. You can define multiple categories for a simple post inside square braces (categories: [cat1, cat2]). 


Now it is time to test our post. Save it and copy it to the _posts directory inside the root of our blog.

Using terminal, start the server.

If did it right, you can see your post. 

Now, you can upload it to your github repo. 

Login to your GitHub account. Open _posts instide your repo.Just drag and drop the file to _posts. Wait for few seconds. You're done.


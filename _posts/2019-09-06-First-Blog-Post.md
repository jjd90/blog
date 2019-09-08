---
layout: post
title:  "First Blog Post"
date:   2019-09-06 22:55:00 -0800
categories: Blog
---

Welcome to my first blog post!

My name is Juan and I am currently a senior majoring in CIT. For this blog post I will be writing about my experience in trying to accomplish the first lab and creating my github blog page. Like most students the process for the lab was smooth up until page 9 when the dreaded error messages began. When logging into the docker container cit160 and using the guest account that I created running the class_setup command would instantly fail.

Being that I couldn’t get the command to complete correctly I moved on to the next steps in which we SSH into the CSUN server and follow the same process which ended up working knowing that I wouldn’t be able to complete the epilogue steps within the cit160 container I opted to run them on the CSUN SSH server which worked and I was able to eventually complete the lab. I ended up copying the lab report file from the CSUN SSH server over to my desktop.

In regards to the blog the overall process for using github page and Jekyll to create an online blog was much more fun than the Lab. Once you learn the basics of how git hub commands work it is a smooth process. You install Jekyll on your machine, then you create the folder and files that will hold all the necessary information for your blog page.

Next, you have to, using github, create a repository and transfer those Jekyll files up onto a master repository. After that you create another branch called “gh-pages” which github will recognize and instantly host the page through the personal web address which in my case is

https://jjd90.github.io/blog/

In conclusion learning github and Jekyll was a fun process for me while using docker and trying to get the lab completed ended up being much more complex than I figured it would. As I write this, I have yet to get the class_setup to run successfully on my docker cit160 container.

Thanks for reading!

[UPDATE]
 I was eventually able to figure it out with the help of the professor. It turned out that I had a bad container and all I needed to do was blow it up and recreate it (mind blown). Then again, the professor had mentioned that containers are designed to be easy create or delete when needed.



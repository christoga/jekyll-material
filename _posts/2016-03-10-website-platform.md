---
layout: post
title: Open your website on different platform
date: 2016-03-05
categories: tips-tricks
author: Andre Christoga
header_image: img/platforms.png
---
Today, I'm going to tell you how to run your web in different platforms without hosting <br>
But.. make sure the platform you will be testing in is in a same wifi network <br>
Step by steps down below:👇

## Responsive
I actually doesn't think that this terminal command will work, <br>
Because I can run my website in phone without pushing to github pages / hosting <br> 

## Step by Steps
Open your terminal and run `ifconfig`(OS X) and `ipconfig` (Windows)
<img src="{{ site.url }}/img/terminal.png" alt="Terminal Output"/>
In the screenshot, you can see my `ip` is `192.168.1.106` <br>
This ip is actually `localhost`, so the url is basicly the same but you have to chance your web address <br>

Example:
My IP = `192.168.1.106` <br>
Web address = `localhost/website` <br>
Type in `192.168.1.106/website` in your phone

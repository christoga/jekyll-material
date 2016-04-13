---
layout: post
title: Deleting a git branch
date: 2016-01-20
categories: tips-tricks
author: Andre Christoga
header_image: img/git.jpg
---
Sometimes I accidently press `enter`,<br> and created a branch named `gh` instead of `gh-pages`.

So I browse something and the command actually works!
Today,<br> I'm gonna give you step-by-step to delete a git branch😀

## What is git
Git is a version control developed by Git (itself),<br> for more documentation,<br> their website is avalaible on [http://git-scm.com]()

## Command Line
The command have two choices,<br> You can use `:` or `--deleted`,<br> the command is down below😀 <br>

### 1. Using `:`
```shell
git push -u origin :branch
```
<br>

### 2. Using `--delete`
```shell
git push -u origin branch --delete
```

### Referensi
[http://js.org]() <br>
[https://github.com/js-org/dns.js.org/wiki]() <br>
[https://github.com/js-org/dns/wiki/Subdomain-Determination]()

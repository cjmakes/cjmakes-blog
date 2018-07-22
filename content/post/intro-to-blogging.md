---
title: "Intro to Blogging"
date: 2018-07-22T14:34:07-04:00
draft: true
---

What
====
Blogging. There are many popular software engineering blogs that give programmers an outlet to discuss and share what they are working on. This is mine

Why
===
It will help me document the projects that I'm working on in a slightly better way than git commit messages like "Fix this thing".

How
===
The why this site is published involves a few moving parts, organized into 2 github repositories. 

# cjmakes-blog
The source lives here in the form of a [hugo](https://gethugo.io) site. This is a static site generator that will take the theme you install as a git submodule (I'm using (hugo-xmin)[https://github.com/yihui/hugo-xmin/]). It takes your content as markdown files and formats it with your themes css & js and then puts the generated site into a `/public` directory.

# cjmakes.com
This is a repo that just hosts generated static content. It is a submodule in `cjmakes-blog` in the `public` directory. So once the static content is generated it can be commit here and pushed to the github repo. Here it is hosted as a github pages site.

# Github pages
I also have a custom domain setting in github pages that takes my dns from cloudflare

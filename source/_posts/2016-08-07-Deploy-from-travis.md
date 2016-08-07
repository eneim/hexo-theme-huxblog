---
title: Auto deploy from Travis CI
subtitle: So I don't need to stay close to my PC all the time.
date: 2016-08-07 20:42:46
tags:
    - Dev
    - Blog
    - EN
    - CI
    - Travis
---

**TL,DR:** I added my blog to Travis CI so every time I push something new to *master branch* of my blog repo, it will automatically generate and deploy my blog.

## Why CI, Why?

> ***Why not?***

Well, this morning when I was in the train going far away from home (to the next station, actually), I would like to post something fun to my new blog. But hey, I don't have my PC connected to the Internet, and if I really want to, I need to tether from my iPhone, which is not something cool. So I thought of how about something that help me to deploy the post after I push it to the repo. So that I can simply post new stuff just from my iPhone.

Well (again), it turns out to be easily done by setting up a CI (Continuous Integration) server, where **Travis CI** is one of the most famous. And most important, when I tried a *Google search* about it, [this tutorial](https://sazzer.github.io/blog/2015/05/04/Deploying-Hexo-to-Github-Pages-with-Travis/) comes to (almost) top. So here I have my blog setup, and after I push this post to the air, I don't have to run the boring ```hexo deploy``` command again.

Just that. Have fun blogging folks.

*P/S*: This post is actually created to test the CI.

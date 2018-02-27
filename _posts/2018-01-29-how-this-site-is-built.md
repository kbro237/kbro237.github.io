---
title: How This Site is Built 
author: Keith Walbolt
date: '2018-01-29 19:00'
tags: tech
layout: post
---

Here's how I post blog posts to `www.netfull.org` and microblog posts to `www.netfull.org/microblog` as well as [Micro.blog](https://micro.blog)...

My blog, this blog, which is trying to tie together the various threads I'm interested in, is now hosted on [Github Pages](https://pages.github.com). It's a static site built by [Jekyll](https://jekyllrb.com/) which means that Github builds it automatically every time I update the files.

The nice thing about building the site this way is it's always under version control so there's always a trail of bread crumbs back to any previous version of the site. I can revert back in time to fix the mistakes I regularly make while coding it. Also, the source is public so you can [see](https://github.com/kbro237/kbro237.github.io) the mistakes yourself.


I've been intrigued by Manton Reese's [Micro.blog](https://micro.blog) project as an independent way to publish little thoughts and to have a little dialogue back and forth. Like the way I  once thought Twitter should work, but without all the baggage. Twitter's annoying attempts at monetization are understandable; Twitter's enabling of White Supremacy, misogyny, and genocidal nuclear threats are unconscionable.

I really recommend you give it a try. I also recommend you pay a few dollars a month and get Micro.blog's hosted service unless you really want to sink some hours into a painful, substandard, DIY system like mine. 


<del>For now 'microblog' posts, which you can think of like Tweets, don't show up in the main JSON/RSS feed or on the homepage. Instead, they live on the Microblog part of my site.</del> To get that set up, I relied heavily on excellent posts by [Tim Smith](https://brightlycolored.org/2017/02/creating-a-microblog-with-jekyll/), [Ross Kimes](http://rosskimes.net/2018/01/microblog/), and [Kirby Turner](https://www.thecave.com/2017/04/21/how-i-post-to-my-jekyll-site-using-my-iphone/). You make fewer mistakes when you stand on the shoulders of others.

**Update:** I'm now putting my microblog posts into the same stream as my blog posts. This required some pretty major changes to the structure of the site since my plugin options are limited on Github Pages. You can now subscribe to just the full (titled) posts, just the microblog posts, or both (the default feed.)

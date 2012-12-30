---
layout: post
title: "How I met Octopress"
date: 2012-12-30 20:24
comments: true
categories: 
---

This blog mainly contains notes of various technics. It has been also
used as a spot for me to share my experiences. 

Originally, this blog was hosted on blogspot. I've decided to migrate the site
to octopress based on Github for the following reasons:

- It's hard to get code syntax highting on blog: There is no native syntax
  highlighting on blgospot. I need to create code snippets and add related js
code in blogspot. Considering the amount of source code in this blog, the
management is a nightmare.
- Blogspot is censored in China: Considering the difficulties of my chinese
  reader, it's better for me to have a full managed blog service, and be able to
switch to other solutions in case my original host is censored.
- Octopress has native Markdown support. It is indeed very pleasant to write
  blog in Markdown with my favoriate editor - vim.

Well, as always, there are still some disadvantags using Octopress

- Most important of all, it's getting impossible to udpate the blog over the
  air. Octopress force me to have a ruby environment in order to update my blog.
  Well, in the same time, the nice thing is that I can update my blog at any time even without internet connection as long as I have my client. :-)

Some other solutions have also been considered, for example:

- [nanoc](http://nanoc.stoneship.org/): Nanoc is a quite nice ruby based static web page generator. It's very
  simple and dynamic for customization. But for me, it took me sometime to check
how to find a nice template, how to make a beautiful source code highlighting,
etc. And it doesn't have a native github support neither (althought it's not a
big issue.) As a summary, it's nice but need sometime to get everything ready
- [middleman](http://middlemanapp.com/): Middleman is also a static site
  generator based on ruby while it's more suitable for a CMS site (afaik)
instead of a blog. The team provided an official extension for blog:
[middleman-blog](http://middlemanapp.com/extensions/blog/) but I didn't try it,
so can't make any comments. It would be nice if it has a nice even native
support for github.
- [ruhoh](http://ruhoh.com/): Ruhoh is another online static web blog service. It's a bit higher
  level than nanoc and doesn't need the whole web pages to be completely
generated. The idea is to host all markdown pages on github and use rohoh
service to generate the final stage html codes for you. A nice feature is that
authors can chose their own developing language and make their own script for
blog management as long as the basic API is followed. It show another thrend but it's not exactly what I am looking for: a service provider indenpendent blog
service.
- [calepin](http://calepin.co/), [Scriptogr.am](http://scriptogr.am/): They provide a similar idea to Octopress, but on dropbox :-) Apparently, I can be more private because dropbox provides some private hosting services. I didn't chose that because anyway I will need github to do the version control of my blog and I don't store the private thing in my blog.

Besides [Octopres](http://octopress.org/) and [Github](http://github.com) I should thank to the community of the following projects which helped me constructing this blog:

- [Slash](http://zespia.tw/Octopress-Theme-Slash/): Slash is a beautiful minimal
  theme for octopress. This blog is using a customized tempalte based on Slash.

References:

- Yifeng RUAN's blog: [How to build an ultimate blog with github + jekyll (in
  chinese)](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
- dBlock.org: [Octopress: Setting up a Blog and Contributing to an Existing
  One](http://code.dblock.org/octopress-setting-up-a-blog-and-contributing-to-an-existing-one)
This blog introduced a useful tip to manage source code and generate static blog
in the same github repository: push the source code to antoher branch
source by using "git push origin source"


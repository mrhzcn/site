---
layout: post
title:  "How to install Jekyll"
date:   2019-06-16 06:39:03 +0300
categories: blog
---

In order to use github pages to maintain your site, you need to install Jekyll in your local machine and commit the files produced by the system. Here is a quick list of things to do in macOS:

* sudo gem install rails
* to install jekyll I also needed sudo
* sudo gem install jekyll bundler
* cd ~/Sites
* jekyll new <foldername>
* cd <foldername> OR cd !$ (that is magic ;)
* bundle install
* bundle exec jekyll serve
* Then in your browser just go to http://127.0.0.1:4000/ and it really should be running
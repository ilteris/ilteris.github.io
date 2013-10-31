---
layout: post
title: "Mavericks YouCompleteMe"
date: 2013-10-29 19:56
comments: true
categories: 
---

If you start getting lots of errors on your YCM plugin for vim, it's most likely
using 10.9. What you need to do is to compile your vim on 10.9. If you are lazy,
go grab macvim and just copy the mvim script that's in the package to your
/usr/local/bin dir. Delete the old vim binary and just create a symlink [ ln -s
/usr/local/bin/mvim /usr/local/bin/vim] and you are good to go.

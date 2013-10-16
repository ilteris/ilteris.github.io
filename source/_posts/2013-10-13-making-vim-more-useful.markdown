---
layout: post
title: "making vim more useful"
date: 2013-10-13 15:12
comments: true
categories: 
---
To make vim more useful and act like bit like emacs, it's possible to install
this plugin called [tslime.vim](https://github.com/teranex/tslime.vim). I have
tried official slime but unfortunately that created a lot of problems with tmux.
This is the only fork that worked on multiple windows multiple panes setup. Once
installed (I use pathogen to install it but you can use whatever you want) you
can use <c c> <c c> to teleport the code to the node that's running in another
pane. It's quite useful.

Another useful plugin is
[YouCompleteMe](https://github.com/Valloric/YouCompleteMe) and
[ultisnips](https://github.com/SirVer/ultisnips). Unfortunately it's not
seamless but it definitely gets the job done. It allows you to choose the
dropdown snippets and allow you to choose those using <c j> and then going
forward/back using <c j> and <c k> in the placeholder variables. There's an
issue that's stated on the github that promises to fix the problem but
unfortunately it doesn't work for vim that runs in the terminal. For it to work
probably one needs macvim. 

[Tern for vim](https://github.com/marijnh/tern_for_vim) is another useful
pluging for doing javascript in vim. For me beside the killer feature is to
allow me to jump to defition of functions. Follow the installation instructions
and then whenever cursor is on a variable or a property TernDef takes you there.
I have just started using it so, at this point scratching the surface. Another
handy vim command ` <c o > ` and ` <c i> ` allows to go jumpback to old cursor
positions if one wants to go back.  

These are all useful additions to vim workspace.

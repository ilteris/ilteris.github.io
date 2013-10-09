---
layout: post
title: "Javascript Dependency Management"
date: 2013-10-02 09:50
comments: true
categories: 
---
Unlike many other languages javascript doesn't have a standard way to import
modules. This made people to come up with different solutions like CommonJS, AMD
or using plain old global namespace. It took me a while to understand what's
going on with the whole dependency management eco-system and what they mean and
how they work. 

Here are a few webpages to grasp it better:

http://yahooeng.tumblr.com/post/62383009835/javascript-modules-amd-and-the-road-ahead

http://blog.startifact.com/posts/overwhelmed-by-javascript-dependencies.html

http://blog.testdouble.com/posts/2013-06-16-unrequired-love.html

http://dontkry.com/posts/code/browserify-and-the-universal-module-definition.html


Generally there are two camps, RequireJS and CommonJS. CommonJS is similar to
how npm but AMD people (RequireJS) think it's a javascript hack and it doesn't
conform to the standards. From the other side, the critization is, RequireJS
adds a lot of headache when project gets bigger. 

It looks like with ECMAScript 6, Javascript folks are going to try to come up
with a cleaner and more important standard way of handling all these tasks. 


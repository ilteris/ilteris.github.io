---
layout: post
title: "Block Objects in iOS"
date: 2013-11-25 09:22:24 -0600
comments: true
categories: 
---

“Block objects can either be inline or coded as independent blocks of code.
Let’s start with the latter type. Suppose you have a method in Objective-C that
accepts two integer values of type NSInteger and returns the difference of the
two values, by subtracting one from the other, as an NSInteger:”

Excerpt From: Nahavandipoor, Vandad. “iOS 7 Programming Cookbook.” iBooks. 

    - (NSInteger) subtract:(NSInteger)paramValue from:(NSInteger)paramFrom { 
    return paramFrom - paramValue;
    }


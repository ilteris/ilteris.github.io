---
layout: post
title: "Parse and Facebook integration for iOS and ideas"
date: 2013-10-30 21:09
comments: true
categories: 
---

Log in facebook in parse allows for read permissions. This doesn't require to
launch facebook app. Simple popup allows this. Instead does everything in the
background. We can pull fb user's id, name etc. with this. We can then link this
to PFuser object in our User table.  Parse allows devellopers to store and link
uploaded photos by users on Parse. This opens up freedom to create applications
to have linked users (by facebook) on Parse. 
One scenario:
                User A logs in with facebook on app X. App X grabs all of his fb
                friend list and save it to Parse. Then, his friend user B logs
                in with facebook using app X. This gives us possibility to send
                a notification to the user A saying, your friend just joined the
                app. 
Birthdays:
          Login with facebook, your friends birthday and get automatic
          notification to your phone.


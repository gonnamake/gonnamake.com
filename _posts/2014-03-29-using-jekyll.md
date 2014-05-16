---
layout: post
title:  "How to use jekyll?"
author: iraycd
date:   2014-03-10 4:49:00
categories: business
featured_image : http://jekyllrb.com/img/logo-2x.png
meta : This is a blog to fellow ninjaas who don't know what is and how to use jekyll. This gives a brief explanation on how to use jekyll and why you should be using it.
tags:
- jekyll
- code
---


##What is jekyll?

Jekyll is a static blogging engine built on ruby. Everything is generated to static files.

    Markdown + YAML + Ruby + Static Pages --> Static HTML


##Why should you use it?

+ It's open source
+ It's markdown which is friendly to developers
+ If you use text editor for most of your writing this is best option.
+ Less caring about the database and dynamic functionality 


##Hosting it?

+ Simple way is to use GitHub Pages.
+ You can entire host as public or private.


##Installating it?

First you need to have ruby on your system. Then you install jekyll
    gem install jekyll
This is a brief tutorial. I won't explain everything learn more yourself.


##Using it?

To run is on a local server.

    jekyll serve

and to watch changes.

    jekyll serve -w

##Adding posts?

If you want to add a post you go to the folder called `_posts`. But, before you start writing you need to give some meta information and meta starts and ends with `---`(3 hyphens).

    ---
    layout: post
    title:  <<Your title will go here>>
    author: <<username>>
    date:   <<YYYY-MM-DD HH:MM:SS(Hope you understand)>>
    categories: <<You can add one of more. If you will add more than one I will will kick you.>>
    featured_image : <<Link to the image>>
    meta : <<Try to add much as information as possible because this is what will do to the search engine. Just kidding but it give more information to the people reading>>
    tags:
    - You
    - Can
    - Add
    - as
    - many
    - you
    - want
    - but
    - beCareful
    ---
    << Your Markdown starts here>>

Don't forget to save the file as `YYYY-MM-DD-<<file_name>>.md`

##Adding drafts?
It's exactly similar to that of post except that you should save the file in folder called `_drafrs` and you can name the file however you want.

##Adding authors?
See the config file you will understand yourself.

##Making plugins?
Don't even care about that now.
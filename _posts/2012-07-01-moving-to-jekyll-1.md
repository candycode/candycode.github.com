---
layout: post
title: Moving to Jekyll
tags: jekyll github
categories: [web-development, jekyll, github]
comments: true
---

#Moving to Jekyll


##Introduction

After trying different solutions to my web publishing needs I ended
up moving to _Jekyll_ and _GitHub_ as the best solution for minimizing
time spent in administering the website and update its content.

I previously used a _WordPress_-based solutions, which, while working
well had simply too many configuration options and required quite a bit
of time to administer and update, not to mention performance issues: even
for small traffic websites quite a bit of resources are required in case
you want to store video and high resolution images on a shared hosting
website:.

Current options:

1. dynamic website w/ shared hosting
2. dynamic website w/ (virtual) dedicated hosting
3. cloud(e.g. Amazon EC2)
3. managed cloud(e.g. Heroku or MediaTemple)
4. static website w/ outsourced services

The best option cleary depends on your needs, I am just now having a hard
time finding cases for the use of (1) and (2), unless you really have
the need to completely control the server side infrastructure and data,
and the expertise to make services scale properly.

The world wide web environment has evolved quite a bit since I started
putting stuff on the internet on a _Geocities_ account back in 1997, and
it is now possible to aggregate services from different providers to
create good-looking and efficient web sites requiring minimal supervision.

Using external web services has of course drawbacks too, like having to react
to interface changes or quirks on different providers. However, not having
to even think about managing databases, email configuration or how to
make pages more responsive it is, I believe, worth the burden.

Note that it is possible to conceive hybrid solutions, like using a

I will describe here the steps I had to go through to create this website
from scratch, host it on GitHub and hook it up with various external services.

#Part 1 - Jekyll on GitHub

_Jekyll_ is a static site generator: create a site layout, content in various
formats such as _Textile_ or _MarkDown_ and have _Jekyll_ generate a fully functional
website. Full documentation is available on the 
[official _Jekyll_ website_](http://jekyllrb.com/).

[_GitHub_](http://github.com) offers a number of ways to host a website:

1. Create a git project <username>.github.com and put some html content in it
2. Create a _gh-pages_ branch of a project and put html documents in such branch

In both cases it is possible to associate a domain name with the web content by
adding a _CNAME_ file in the root directory of the repository containing the name
of the domain.

Also, at each _git push_ the uploaded content is run through _Jekyll_ by default
and a new version of the website created.

The only caveat to using _GitHub_ to generate the actual website content through
_Jekyll_ is to avoid any _Jekyll_ plugin.


There are a few ways to proceed when using _Jekyll_ to generate your website,
some are:

1. do everything in the branch that mirrors the _gh-pages_ or <username>.github.com
branch on the _GitHub_ server

2. create a separate development branch and merge with the main branch when you
want to update the content on the website

I am currently using solution (2) because it allows me to slowly update content
without impacting the integrity of the main site; it also allows to use _Jekyll_
to generate the website on my PC and upload the generated content later.

Note that although you do not technically need _Jekyll_ installed on your computer,
in practice you do, because you do want to check how the website looks before
updating it on the server. Exceptions include blog-only sites, where after the initial
setup the only part that is updated is the blog section. 

 
##Step 1: site layout

##Step 2: content

##Step 3: configuration

##Step 4: test and upload

---

#Part 2 blog

---

#Part 3 feeds and forms

---

#Part 4 other

---

###Images(gallery)
###Videos
###MathJax

---

#Part 5 advanced

###Custom fields
###Customized navigation (specify navigation as associative array) 









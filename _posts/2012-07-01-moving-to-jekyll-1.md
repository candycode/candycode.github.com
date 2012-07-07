---
layout: post
title: Moving to Jekyll - Introduction
tags: jekyll github
categories: [web-development, jekyll, github]
comments: true
---

After trying different solutions to my web publishing needs I ended up
choosing _Jekyll_ and _GitHub_ as the best option for minimizing
the time spent in administering the website and updating its content.

I previously employed a _WordPress_-based solution, which, while working
well, had simply too many configuration options and required a considerable amount
of time to administer and update, not to mention performance issues: even
for small traffic websites quite a bit of resources are required in case
you want to store dynamic content, where each _HTTP_ request is basically
a database query, and serve video and high resolution images all from a 
a shared hosting service.

This is the first of a series of articles where I describe the steps 
I had to go through to create this website from scratch, 
host it on _GitHub_ and hook it up with various external services to
add _RSS_ feeds, discussions and contact forms.

Let's start by looking at what are the options available for hosting
a website.

##Website hosting options

The current options for hosting a website with services such as _RSS_ feeds,
weblog and forms are:

1. dynamic website with shared hosting
2. dynamic website with (virtual) dedicated hosting
3. cloud(e.g. Amazon EC2)
3. managed cloud(e.g. Heroku or MediaTemple)
4. static website with outsourced services

The best option cleary depends on your needs, I am just now having a hard
time finding cases for the use of (1) and (2), unless you really have
the need to completely control the server side infrastructure and data,
and the expertise to make services scale properly.

The _World Wide Web_ ecosystem has evolved quite a bit since I started
putting stuff on the internet on a _Geocities_ account back in 1997, and
it is now possible to aggregate services from different providers to
create professional looking and efficient web sites requiring minimal supervision.

Using external services has of course drawbacks too, like having to react
to interface changes or quirks from different providers. However, not having
to even think about managing databases, email configuration or how to
make pages more responsive it is, I believe, worth the burden.

Note that it is possible to conceive hybrid solutions as well, like using a
separate website to update the content on the main website dynamically: e.g.
use a web/REST front-end to create blog articles inside a git repository and
synchronize the repository with the _GitHub_ project hosting the website.


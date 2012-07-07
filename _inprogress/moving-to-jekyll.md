
-------------------

#Part 1 - Jekyll on GitHub

_Jekyll_ is a static website generator: create a site layout in the filesystem, 
content in various formats such as _Textile_ or _MarkDown_ and have _Jekyll_ 
generate a fully functional website. Full documentation is available on the 
[official _Jekyll_ website_](http://jekyllrb.com/).

[_GitHub_](http://github.com) offers a number of ways to host a website:

1. Create a git project <username>.github.com and put some html content in it
2. Create a _gh-pages_ branch of a project and put html documents in such branch

In both cases it is possible to associate a domain name with the web content by
adding a _CNAME_ file in the root directory of the repository containing the name
of the domain.

Also, at each _git push_ the uploaded content is run through _Jekyll_ by default
and a new version of the website is created.

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
to generate the website on my PC and upload the generated content later, which
is required anyway should you want to use plugins; I am not currently using
any additional plugin though.

Note that although you do not technically need _Jekyll_ installed on your computer,
in practice you do, because you do want to check how the website looks like before
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

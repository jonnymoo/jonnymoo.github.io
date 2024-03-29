[![Build Status](https://travis-ci.org/jonnymoo/jonnymoo.github.io.png)](https://travis-ci.org/jonnymoo/jonnymoo.github.io)

# Contribution guideliness

:tada: First off, thanks for taking the time to contribute! :tada:

Here are some links to help your way around the repo. Do raise an [issue](https://github.com/jonnymoo/jonnymoo.github.io/issues) if you're ever unsure of anything - we'll help get things sorted together.

## Creating a blog post

1. Make a new post in a text editor
2. Your post should **always begin with**  
```
---  
layout: post  
---
```
3. **Save it as a ```.md``` file**
4. Your file name should **always start with a date**; ie. ```2018-04-11-Blog-Title.md```

**Remember!** You can always look at previous posts for examples if you're unsure.

[```_posts```](https://github.com/jonnymoo/jonnymoo.github.io/tree/master/_posts) - We put all blog posts in this folder.

[assets](https://github.com/jonnymoo/jonnymoo.github.io/tree/master/assets) - We put all our images in here. You can create folders if you want to group them together.


## Layout & other pages

[default.html](https://github.com/jonnymoo/jonnymoo.github.io/blob/master/_layouts/default.html) - Change the layout of the website and navigation bars.

[style.css](https://github.com/jonnymoo/jonnymoo.github.io/blob/master/css/style.css) - Change the design and colour of things on the website.

## Running locally

[Install all the stuff jekyll needs as described](https://jekyllrb.com/docs/)

Then 

     bundle exec jekyll serve

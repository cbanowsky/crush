# javathehut.net Ghost Theme

## based on [Casper](https://github.com/TryGhost/Casper)


This is a Casper-based Ghost theme that I am using for javathehut.net. Google Analytics on every page and Disqus built in for comments.  

## Install 

`git clone https://github.com/PoopBaron/ghost-hut /path/to/Ghost/content/themes/ghost-hut`

## Setting up Analytics

Assuming you did everything right on the Google-end of things, just enter your tracking id i.e.  `UA-XX...` into the Analytics javascript located in `default.hbs`   

To get disqus working just insert your disqus shortname into the disqus script located in `post.hbs`.

after that run `grunt` 
change to Ghost root direcotry
if your blog is still in development then `npm install` should be all you need.

I am still working on adding some more features/cleaning up the stylesheets...initial commit is for those who don't mind making their own modifications.


enjoy.
 



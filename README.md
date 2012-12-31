github-pages-jekyll-example
===========================

About
-----

Example of blog powered by jekyll runnable on github pages. Unlike
other examples this one takes a different approach, site is generated
locally and the result is pushed into the respository.

Other examples I have found so far are without pygments and syntax
highlighting, pagination and github flavored markdown.

Additional requirements to jekyll
---------------------------------

Install redcarpet. Redcarpet is markdown parser used on github.
Github Pages are using older version.

    sudo gem install redcarpet
    
Install pygments, great tool/library for syntax highlighting.
    
    sudo easy_install pygments
    
**(already included)** Generate css file if you think that
the file included is not up-to-date.
    
    pygmentize -S default -f html > css/pygments.css
    
**(optional and recommended)** Download and setup
[git-publish-pages tool](https://github.com/prost87/git-publish-pages).
It makes copying of generated static site to gh-pages branch a piece of cake.

Problems?
---------

If you have found a bug or missing feature, fill a bug, please.
Or just fork it, fix it and request pull.

License
-------

MIT license.
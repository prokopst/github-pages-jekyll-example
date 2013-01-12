github-pages-jekyll-example
===========================

About
-----

Example of project site powered by jekyll runnable on github pages.
Unlike other examples this one takes a different approach, it's
is generated locally and the result is pushed into the respository.
This way you can use the latest versions of liquid, jekyll and redcarpet.
You can even use plugins from _plugins directory. So you are not
limited and you can do any wild stuff you want.

Additional requirements to jekyll
---------------------------------

Install redcarpet. Redcarpet is markdown parser used by github.

    sudo gem install redcarpet
    
Install pygments, great tool/library for syntax highlighting.
Note that jekyll will implicitly inject pygments to redcarpet,
if pygments are used in configuration.
    
    sudo easy_install pygments
    
**(already included)** Generate css file if you think that
the file included is not up-to-date.
    
    pygmentize -S default -f html > css/pygments.css
    
**(optional but recommended)** Download and setup
[git-publish-pages tool](https://github.com/prost87/git-publish-pages).
It makes copying of generated static site to a different branch a piece
of cake.

Problems?
---------

If you have found a bug or missing feature, fill a bug, please.
Or just fork it, fix it and request pull.

License
-------

MIT license.
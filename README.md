Physics in JS
=============

Updated 2015 March 26

This repository hosts code examples from Burak Kanber's _Physics in
JavaScript_ blog series at http://burakkanber.com/blog. The series teaches the
fundamentals of physics through a common, easy language that most web developers
know: javascript.

Read the introductory blog post here: http://burakkanber.com/blog/modeling-physics-in-javascript-introduction/

This repository simply rehosts the javascript examples. Please note that many
of the examples were written in 2012 or earlier, and still need updating in
terms of good modern JS practices. And since these examples were first hosted
on JSFiddle.net, the source isn't well-organized. I hope to, over time, clean
up this repository and modernize the code.

Directory Structure
-------------------

Each directory represents a physics topic. Topics with only one
example will contain that example in `{folder}/index.html`, while topics with
multiple examples will split them up into files named `part1.html`, etc.

All assets required to run the examples, with the exception of CDN-hosted
jQuery, are in the folders as well.

Each folder contains a `README.md` file, which briefly describes the topic and
provides a link to the blog article(s) that accompany each topic. For now, the
articles are hosted on the blog. Eventually I'll convert them to markdown and
store them in this repository too.

Running the Examples
--------------------

I don't have a Github Pages site set up for this yet, so for now clone the
repository and use your favorite web server to serve this directory. My
favorite is `$ python -m SimpleHTTPServer`.

To-Do
-----

- Write README.md's for each folder.
- Modernize the examples.
- Set up a GitHub Pages site for this repository.
- Convert blog posts to markdown and provide them in this repository.

License
-------

All code in this repository is free for educational use but prohibited for
commercial use or any other purpose.

License Notes:

If you would like to use one of these algorithms, write your own
implementation! That's the whole point of this series. I want you to learn the
algorithms presented, and that means writing your own implementation of them.

And if you need to use any of these algorithms in production, please use a
well-known, well-maintained open source project. This code isn't maintained,
and it's not optimized for mission-critical use.

That's why this license is so restrictive. Not because I don't want you to use
this code, but because you _shouldn't_.


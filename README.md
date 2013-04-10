Dave's models
===============

So as soon as I saw that GitHub supported [STL file viewing](https://github.com/blog/1465-stl-file-viewing)
in a repository, I had to try it out.


My teapot
-----------
The first model I've uploaded is my teapot model.  

If you're at all familiar with the history of 3d computer graphics you'll 
know about Martin Newell's [Utah Teapot](http://www.computerhistory.org/revolution/computer-graphics-music-and-art/15/206) model.  While he was a grad student 
at the University of Utah he made a Bezier patch model of his teapot.  It is
used all over computer graphics.

Some years ago my friend and colleague got ahold of Newell's actual teapot.
He borrowed it from a computer museum, if I recall correctly, took it to
a med school and stuck it in a CT scanner.

My teapot model is an iso-surface extracted from that CT scan.  If you've
seen the original teapot model, it looks sort of like the actual teapot, but not
too closely.  Also the graphics teapot is squished compared to the actual teapot.
I think it had something to do with compensating for non-square pixels of the
raster displays back then.


The Visible Male head
------------------------
I was trying to figure out if GitHub's STL renderer had any support for color STL
models.  STL doesn't really support color, but if you read the [Wikipedia description
of the STL format](http://en.wikipedia.org/wiki/STL_(file_format)), 
you can see that several different companies have kind of hacked it
into the binary verion of the format.  I tried putting color in a STL mesh to see
if it would show up, but it didn't work.  Too bad.

My color test model is of the [Visible Male](http://www.nlm.nih.gov/research/visible/visible_human.html) 
head, produced by the [Office of High
Performance Computing and Communication](http://lhncbc.nlm.nih.gov/ohpcc/)
at the [National Library of Medicine](http://www.nlm.nih.gov)
(where I work).  I made this head model from the cryogenic images.  In the model
I made a cut-out of the head so you can see the brain and optic nerve.  Sadly
since color is not supported by STL, it's not really there in this version.

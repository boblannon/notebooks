notebooks
=========

Collection of presentations and musings in the form of iPython notebooks

If you've never heard of it, here's an (outdated) but decent video that's a quick intro to the iPython notebook and what it can do:

>> http://www.youtube.com/watch?v=DUCQ_HZamhs

To host a notebook locally (so that you can play with it), you'll need to set up:

* iPython >= v0.13 
* "other dependencies"[http://ipython.org/ipython-doc/stable/install/install.html#dependencies-for-the-ipython-html-notebook]

Dependencies
------------
Didn't want to make one single requirements.txt, but maybe I'll make a bunch of different ones? In the meantime, if you get an import error, here's some stuff you might not have:

* the major scientific computing packages (SciPy, NumPy, Scikit-learn, etc) 
    * The easiest way to get most of this stuff is to install the "Enthought Python Distribution"[http://www.enthought.com/products/epd.php]
    * that's not necessary, though: you can absolutely 
* nltk
    * in PyPi
    * you may have to download some of the corpus resources: http://nltk.org/api/nltk.html#module-nltk.downloader
* pandas
    * also in PyPi
    * wes mckinney's book also describes good ways to set up your environment with EPD

Running a notebook
------------------
If you think you're set up, cd to the same dir as the .pynb that you want to see and run 

    ipython notebook --pylab inline 8888

A browser might pop up and give you a UI. if not, you can always go to http://locahost:8888

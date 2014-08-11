Scientific Computing and Visualization Course (Fitchburg State University, Fall 2014)
=======

This is a repository for much of the material for Math 3001, Scientic Computing, a topics course at Fitchburg State University during Fall 2014. This is an introductory course requiring some basic Calculus and programming knowledge. 

Getting Started
-----------
This course will use the [Julia Language](http://julialang.org), a new language specifically designed for scientific computations.  Follow the steps in the [MIT Install Manual]() to install Julia on your computer. 

Documentation and Code
-----------

Documentation and code will be posted here on a weekly basis in folders.  You can browse the documentation within each folder or, as is recommended, clone this repository via git.  Then you can easily keep up to date.  See [using git and SourceTree](#git) for help with this.


Installing Julia and IJulia
------------

Note: this is based on the [Using Julia at MIT](https://github.com/stevengj/julia-mit/):

1. First, install iPython and related scientific-Python packages (SciPy and Matplotlib). The simplest way to do this on Mac and Windows is by [downloading the Anaconda package](http://continuum.io/downloads) and running its installer. (Do not use Enthought Canopy/EPD.)

	**Important:** on Windows, the Anaconda installer window gives options Add Anaconda to the System Path and also Register Anaconda as default Python version of the system. Be sure to check these boxes.

	If you do not want to install via Anaconda, [IPython has downloads as well.](http://ipython.org/install.html)

2. Second, download Julia version 0.3 (which is in the 3rd release candidate as of Aug 12, 2014) and run the installer. Do not download version 0.1. Then run the Julia application (double-click on it); a window with a julia> prompt will appear. At the prompt, type:

```
Pkg.add("IJulia")
Pkg.add("PyPlot")
```

If you are having trouble, try the [Using Julia at MIT](https://github.com/stevengj/julia-mit/) site and search for "troubleshooting" on the page.  

<a name="git"></a>
Use Git and SourceTree
-----------

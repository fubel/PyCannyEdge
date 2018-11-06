PythonCannyEdge
----------------------

[![GitHub release](https://img.shields.io/github/release/fubel/PyCannyEdge.svg)](https://github.com/fubel/PyCannyEdge/releases/tag/v1.0)

This repository contains an **educational** implementation of the Canny Edge Detector in Python 2.7. I wrote this to generate plots for my Bachelor's thesis about Numerical Edge Detection and not for productive applications. 

The algorithm was splitted in it's 5 essential parts. You can find the corresponding functions in [``CannyEdge/core.py``](CannyEdge/core.py). 


Usage
-----

> **Requirements:**
> You need to have [Python 2.7](https://www.python.org/), [Numpy](http://www.numpy.org/), [SciPy](https://www.scipy.org/) and the [Matplotlib](http://matplotlib.org/) installed.
> You can also use [Python Anaconda](https://www.continuum.io/downloads) which already includes all those libraries.

- To generate the Edge Image of ``lena.jpg``, call `python detector.py lena.jpg 1.4 20 40`
- For general usage, call ``python detector.py -h``

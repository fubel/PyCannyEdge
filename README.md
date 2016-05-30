PythonCannyEdge
----------------------

This repository contains an **educational** implementation of the Canny Edge Detector in Python 2.7. I wrote this to generate plots for my Bachelor's thesis about Numerical Edge Detection and not for productive applications. 

The algorithm was split in it's 5 essential parts. You can find the corresponding functions in [``CannyEdge/core.py``](CannyEdge/core.py). 


Usage
-----

> **Requirements:**
> You need to have [Python 2.7](https://www.python.org/), [Numpy](http://www.numpy.org/), [SciPy](https://www.scipy.org/) and the [Matplotlib](http://matplotlib.org/) installed.
> This repository doesn't come with a virtualenv unfortunately, because neither Numpy nor SciPy work with virtualenvs very well. But this is certainly on the todo-list.

- To generate the Edge Image of ``lena.jpg``, call `python detector.py lena.jpg 1.4 20 40`
- For general usage, call ``python detector.py -h``


Todo-List
---------

The purpose of this educational implementation is to help people understand how Canny Edge Detection works. The problem is that the easier algorithms for Non-Maximum Suppression and Edge Tracking have a bad runtime (O(N^2) each for a square image). It would be nice to collect other algorithms that have a better runtime (O(n log n)):

- [ ] Add another, [more efficient](https://pdfs.semanticscholar.org/52ca/4ed04d1d9dba3e6ae30717898276735e0b79.pdf) Non-Maximum Suppression Algorithm 
- [ ] Add another, more efficient Edge Tracking algorithm
- [ ] Create a virtualenv for this project

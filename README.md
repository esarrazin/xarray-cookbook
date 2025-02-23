Xarray cookbook
===============

[xarray](https://docs.xarray.dev/en/stable/index.html) introduces labels in the form of dimensions, 
coordinates and attributes on top of raw NumPy-like multidimensional arrays, 
which allows for a more intuitive, more concise, and less error-prone developer experience.

The goal of this cookbook is to give you some concrete examples for
getting started with xarray. The [docs](https://docs.xarray.dev/en/stable/index.html)
are really comprehensive. 


Table of Contents
=================


* [Chapter 1: Data structures and selection](cookbook/Chapter%201%20-%20Data%20structures%20and%20selection.ipynb)
  <br> Manipulate xarray data structures (DataArray and Dataset), select data
* [Chapter 2: Data computation](cookbook/Chapter%201%20-%20Data%20computation.ipynb)
  <br> How to use xarray data structures for computation
* [Chapter 3: Advanced data computation](cookbook/Chapter%201%20-%20Advanced%20data%20computation.ipynb)
  <br> How to use xarray data structures for advanced computation

How to use this cookbook
========================

To install locally, you can get [pixi](https://pixi.sh/latest/). 

```bash
git clone https://github.com/esarrazin/xarray-cookbook.git
cd xarray-cookbook
pixi install
pixi shell
jupyter-lab
```

A tab should open up in your browser at `http://localhost:8888`

Happy xarray!

License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)


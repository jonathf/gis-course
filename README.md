# Introduction to GIS in Python

GDAL is one of the most popular software libraries in C++ for working with GIS.
Though, it has binding in Python, it is not very *Pythonic*.
To operate GDAL in Python more easily, we have `rasterio`, a frontend to GDAL's
rastering features; `fiona`, a frontend to GDAL's vector features; and `pyproj`
a Python frontend to the `Proj.4` library. This tutorial gives a short
introduction to all three packages.

The tutorial is written in `Jupyter`/`Ipython notebook`. Start a session as
follows:
```
$ ipython3 notebook
```
Browse and find and open the file `course.ipynb`.

## Installation

The installation bellow assumes that the packages `numpy`, `scipy` and
`matplotlib` are all installed.  (See http://scipy.org/ for more information on
these packages.)

The code used in the tutorial is all done in `Python3`. If your system uses
`Python2` by default, use `pip3` instead of `pip` to install libraries.

### Installation in Windows

Download GDAL from:
`http://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal`

Download Rasterio from:
`http://www.lfd.uci.edu/~gohlke/pythonlibs/#rasterio`

Download Fiona from:
`http://www.lfd.uci.edu/~gohlke/pythonlibs/#fiona`

Download Pyproj from:
`http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyproj`

Install binaries:
```
pip install -U pip
pip install GDAL-2.0.2-cp35-none-win32.whl
pip install rasterio-0.31.0-cp35-none-win32.whl
pip install Fiona-1.6.3-cp35-none-win32.whl
pip install pyproj-1.9.5-cp35-none-win32.whl
```

### Installation in OSX

```
brew install gdal
pip install rasterio
pip install fiona
pip isntall pyproj
```

### Installation in Ubuntu

Add PPA (not needed in 15.10):
```
sudo add-apt-repository ppa:ubuntugis/ppa
sudo apt-get update
```

Install GDAL library:
```
sudo apt-get install libgdal1h gdal-bin libgdal-dev
```

Install packages:
```
sudo pip install rasterio
sudo pip install fiona
sudo pip install pyproj
```

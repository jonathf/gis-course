# Introduction to GIS in Python

## Installation in Windows

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

## Installation in OSX

```
brew install gdal
pip install rasterio
pip install fiona
pip isntall pyproj
```

## Installation in Ubuntu

Add PPA (not needed in 15.10 at least):
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

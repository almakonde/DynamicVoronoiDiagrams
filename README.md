
# Voronoi diagram implementation in C++

Slight tweaks to Ivan Kutskir's implementation of Fortune's Voronoi-diagram-building
algorithm (from <http://blog.ivank.net/fortunes-algorithm-and-implementation.html>)
to allow it to be compiled easily on Linux. (Plus translation of an error message
to English, using Google Translate.)
Copyright (C) Almagul Kondubayeva 2021


## requirements

Usual C++ build tools - g++, GNU make, etc.

Headers and libraries for the OpenGL GLUT and GLEW libraries.
On ubuntu, these can be installed with:

```
sudo apt-get install freeglut3-dev libglew-dev
```

## to build

```
make
```

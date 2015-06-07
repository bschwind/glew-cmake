GLEW-CMake
========

This is just a simple CMake version of GLEW, intended to make it easy to build 32/64 bit and shared/static versions of GLEW. It's mainly intended for use within [GFK](https://github.com/bschwind/gfk)

Dependencies
-------------------
- CMake
- A working C++ compiler with C++11 support
- OpenGL
- X11 for Linux

Build
------
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make

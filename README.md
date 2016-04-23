Description
-----------
A complete OpenCascade based MESH framework. Fork from https://github.com/tpaviot/smesh. This fork is intended for easy support of Netgen.

Requirements
------------

  * a c++ and a c

  * cmake 2.8 or higher

  * oce 0.16.1

Build
-----

    $ cd netgen
    $ ./configure --enable-occ --disable-gui --enable-nglib --with-occ=/usr/local
    $ make
    $ make install
    $ cd ..
    $ mkdir build
    $ cd build
    $ cmake ..
    $ make
    $ make install

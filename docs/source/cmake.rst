cmake
=====

https://medium.com/@yulin_li/how-to-update-cmake-on-ubuntu-9602521deecb

https://cmake.org/download/

.. code:: Bash

   tar -xzvf cmake-3.22.1.tar.gz
   cd cmake-3.22.1
   ./bootstrap
   make -j$(nproc)
   sudo make install

Cannot find appropriate C compiler on this system.

sudo apt-get install build-essential

Could not find OpenSSL.  Install an OpenSSL development

As mentioned by others, on Ubuntu you should run

sudo apt install libssl-dev
But for me that was not enough, because although the libraries needed for building were installed, 
they still could not be found. What I had to install in addition was

sudo apt install pkg-config



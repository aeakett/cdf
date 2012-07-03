# cdf

Originally from [http://bmp-plugins.berlios.de/misc/cdf/cdf.html](http://bmp-plugins.berlios.de/misc/cdf/cdf.html).

From the original README:

cdf means "colorized df". The main features of cdf are:

* customazable color schemes
* eye-friendly capacity bars
* most of such utils needs some 3rd party libraries, python interpreter and so on, while cdf written in pure C

## Installation

While I haven't tested the assumption, cdf should compile just about anywhere with a C compiler.
The standard configure;make;make install compiles a single executable and places it /usr/local/bin.
To place it in ~/bin. do:
   ./configure --prefix=$HOME; make; make install

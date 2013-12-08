dbslayer patched
================

once you have replicated this repo
you'll need the following pacakges installed before you can compile

use apt-get to install these packages

mysql-client-core-5.5 libapr1-dev libaprutil1-dev apache2-utils autoconf

e.g.

sudo apt-get install mysql-client-core-5.5 libapr1-dev libaprutil1-dev apache2-utils autoconf

then do a

./configure
make
sudo make install


Other instructions can be found in the INSTALL file

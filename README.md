fileflags
=========

Convert a decimal value into its respective o_flag's.

Usage
-----

    fileflags <flag int>

Example
-------

    ~$ fileflags 8513
     8513: O_WRONLY|O_DSYNC|O_CREAT|O_LARGEFILE

Installation
------------

Tested on SmartOS

    make
    make install

Credits
-------

Taken from http://src.illumos.org/source/xref/illumos-gate/usr/src/cmd/ptools/pfiles/pfiles.c

See source for License

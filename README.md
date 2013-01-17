sim-cache-mod
=============

Topics In Computer Architecture (Fall 2012) - Final Project - Modification to sim-cache to add support for third level caches.

Configuration
-------------

To compile this modified version of sim-cache, you will need a downloaded/
untar'd simplesim-3.0 package. Extract it to the directory of your
choosing, and have the directory location on hand. simplesim also needs
to be preconfigured for the target platform, as per simplesim directions.

You will need to configure ant to know where simplesim is. You can do
this by running:

	$ ant config

If you attempt to run `ant` without running `ant config` first, ant
will tell you to run `ant config` first.

Compilation
-----------

To build, run:

	$ ant

Output
------

When you have built successfully, a new `sim-cache` executable will be placed
within the `build` directory. Your original simplesim distribution should be
unmodified.

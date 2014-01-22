lxc-startup
===========

Script that starts up a container.

That script permits you take you container in a pendrive and run it without copy it to HD. The tree should be like this:

./test.lxc      # The script.

./test/config   # Configuration of container.

./test/rootfs/  # Root directory of container system.


You can start the 'test' container using:

./test.lxc

After, you can see the console using:

./test.lxc console

In order to stop:

./test.lxc stop

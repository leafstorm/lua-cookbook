.. _linux-install:

=======================
Installing Lua on Linux
=======================

.. author:: Alexander Gladysh <agladysh@gmail.com>

.. This is a stub article, intended for demonstration purposes. The real
   article should probably be written from scratch.

This article covers installing Lua on the many flavors of Linux.

Installing from your distribution
=================================
Most Linux distributions nowadays package Lua. If you don't need a customized
build, you can use your distribution's package manager to install it quickly
without building from source.

* Ubuntu, Debian, and derivatives: ``sudo apt-get install lua``
* Fedora: ``yum install lua`` (must be run as root)
* Arch Linux: ``pacman -S lua`` (must be run as root)

If your distribution is not listed, use your package manager to search for
Lua.

.. warning::

    Some distributions also package various Lua libraries. However, for Lua
    development, it's generally better to use LuaRocks and build and install
    them yourself.


Building from source
====================
The Lua source distribution offers a target optimized for building on Linux.

.. sourcecode:: console

    $ wget http://www.lua.org/ftp/lua-5.1.4.tar.gz  # or another downloader
    $ tar -xzf lua-5.1.4.tar.gz
    $ cd lua-5.1.4
    $ make linux
    ...if your distribution uses sudo
    $ sudo make install
    ...otherwise, elevate to root and run
    # make install

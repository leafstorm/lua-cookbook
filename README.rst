============
Lua Cookbook
============
This is the Lua Cookbook, a community-edited collection of useful advice and
"recipes" for working with `Lua`_.

The book is edited using `Sphinx`_. Sphinx requires Python 2.4 or higher to
be installed (if you don't know, run ``python --version`` and see what prints
out). If you have setuptools or distribute installed, run
``easy_install Sphinx``. Your Linux distribution may also provide a Sphinx
package (probably called ``python-sphinx`` or something similar).

.. warning::

    There is also a search engine called Sphinx, please do not confuse the
    two.

To compile the book to HTML, change to the appropriate language
directory (right now there is only ``en``, but in the future we may translate
into other languages) and run ``make html``. The generated files will be in
``build/html``. The Makefile has other options for generating LaTeX source
code, ePub books, and other tasks, run ``make`` without options to see those.

The content of this book is licensed under the Creative Commons Attribution
3.0 license - see the COPYRIGHT file for details.

For information on contributing, visit our `project on Github`_.

.. _Lua: http://www.lua.org/
.. _Sphinx: http://sphinx.pocoo.org/
.. _project on Github: http://github.com/lua-cookbook/lua-cookbook

Praekelt Public Eggs
====================

Simple custom Praekelt PyPi instance served through GitHub.

Usage
-----

To release an egg follow these steps:

#. Compile the egg or create a tarball::

    $ python setup.py bdist_egg sdist

#. Upload the created egg or tarball via this repo's `downloads page <https://github.com/praekelt/public-eggs/downloads>`_.

#. Update ``index.html`` in the ``gh-pages`` branch to include your new download link. Edit straight through GitHub web `here <https://github.com/praekelt/public-eggs/blob/gh-pages/index.html>`_.

http://praekelt.github.com/public-eggs/

#. Specify `http://praekelt.github.com/public-eggs/`_ as your find-link.

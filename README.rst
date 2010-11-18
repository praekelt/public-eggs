Praekelt Public Eggs
====================

**Simple custom Praekelt PyPi instance served through GitHub.**

Usage
-----

To release a Python package follow these steps:

#. Compile the egg or create a tarball::

    $ python setup.py bdist_egg sdist

#. Upload the created egg or tarball via this repo's `downloads page <https://github.com/praekelt/public-eggs/downloads>`_.

#. Update ``index.html`` in the ``gh-pages`` branch to include your new upload's download link. TIP: you can do this quickly by editing straight through GitHub's web interface `here <https://github.com/praekelt/public-eggs/blob/gh-pages/index.html>`_.

#. Add http://praekelt.github.com/public-eggs/ as one of your find-links, or add a dependency_link straight to your new upload's download link.

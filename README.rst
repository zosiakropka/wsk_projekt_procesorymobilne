=====
HOWTO
=====

To generate documentation one needs Sphinx installed.

Installation
------------

Install Sphinx:

.. code-block:: bash

	easy-install -U Sphinx

Compilation
-----------

Documentation compiled with `make` command will be found under `build` directory. Each target format has its own directory inside `build` dir.

Generating PDF documentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

	make latexpdf

Generating HTML documentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: bash

	make html

Syntax overview
~~~~~~~~~~~~~~~

Basic RST syntax can be found under: `Restructured Text (reST) and Sphinx CheatSheet <http://openalea.gforge.inria.fr/doc/openalea/doc/_build/html/source/sphinx/rest_syntax.html#restructured-text-rest-and-sphinx-cheatsheet>`


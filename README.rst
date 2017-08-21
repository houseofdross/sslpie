SSLPie: a CLI, openssl-like tool for humans
###########################################

SSLPie (pronounced *ess-ess-ell-pie*) is a command line TLS/SSL client.
Its goal is to make CLI interaction with ssl certificates as human-friendly
as possible. It provides a simple ``ssl`` command that allows for querying
SSL/TLS certificates using a simple and natural syntax, and displays
colorized output. SSLPie can be used for testing, debugging, and
generally interacting with certificates.

This project was shamelessly ripped off from the amazing HTTPie project
at https://httpie.org/

.. contents::

.. section-numbering::


Main features
=============

* Expressive and intuitive syntax
* Formatted and colorized terminal output
* Quering arbitrary servers and IPs
* Server Name Indication support

Installation
============


macOS
-----

TODO

Linux
-----

TODO

Windows, etc.
-------------

TODO

Python version
--------------

Python 3 is the only version supported at this time


Usage
=====


Hello World:


.. code-block:: bash

    $ ssl www.google.com


Synopsis:

.. code-block:: bash

    $ ssl [flags] domain


See also ``ssl --help``.


Examples
--------

Specifying which server to query for certificate information using the server parameter:

.. code-block:: bash

    $ ssl --server 216.58.203.100 www.google.com


Terminal output
===============

SSLPie does several things by default in order to make its terminal output
easy to read.


Colors and formatting
---------------------

TODO


User support
------------

Please use the following support channels:

* `GitHub issues <https://github.com/houseofdross/sslpie/issues>`_
  for bug reports and feature requests.


Related projects
----------------

Dependencies
~~~~~~~~~~~~

Under the hood, HTTPie uses these two amazing libraries:

* `Requests <http://python-requests.org>`_
  — Python HTTP library for humans
* `Pygments <http://pygments.org/>`_
  — Python syntax highlighter


Contributing
------------

See `CONTRIBUTING.rst <https://github.com/houseofdross/sslpie/blob/master/CONTRIBUTING.rst>`_.


Change log
----------

See `CHANGELOG <https://github.com/houseofdross/sslpie/blob/master/CHANGELOG.rst>`_.



Licence
-------

MIT: `LICENSE <https://github.com/houseofdross/sslpie/blob/master/LICENSE>`_.



Authors
-------

Matthew Wheeler  (`@afoozle`_) created HTTPie and `these fine people`_
have contributed.


.. _pip: https://pip.pypa.io/en/stable/installing/
.. _these fine people: https://github.com/houseofdross/sslpie/contributors
.. _@afoozle: https://twitter.com/afoozle




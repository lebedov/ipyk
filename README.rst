.. -*- rst -*-

IPyk
====

Package Description
-------------------
IPyk is a command line utility for managing locally run IPython kernels.

.. image:: https://pypip.in/version/ipyk/badge.png
    :target: https://pypi.python.org/pypi/ipyk
    :alt: Latest Version
.. image:: https://pypip.in/d/ipyk/badge.png
    :target: https://pypi.python.org/pypi/ipyk
    :alt: Downloads

Installation
------------
If you have `pip <http://www.pip-installer.org/>`_ installed, run::
  
    pip install ipyk

You can also download the source tarball, unpack, and run::

    python setup.py install

Usage
-----
Start a new kernel using the default IPython profile: ::
    
    ipyk -s

List running kernels: ::

    ipyk -l
    0: /home/lebedov/.ipython/profile_default/security/kernel-12345.json

Connect to a running kernel: ::

    ipyk -c 0

Terminate a running kernel: ::

    ipyk -k 0

Author
------
See the included AUTHORS.rst file for more information.

License
-------
This software is licensed under the
`BSD License <http://www.opensource.org/licenses/bsd-license>`_.
See the included LICENSE.rst file for more information.

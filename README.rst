.. -*- rst -*-

IPyk
====

Package Description
-------------------
IPyk is a command line utility for managing locally run IPython kernels.

Usage
-----
Start a new kernel using the default IPython profile: ::
    
    ipyk.py -s

List running kernels: ::

    ipyk.py -l
    0: /home/lebedov/.ipython/profile_default/security/kernel-12345.json

Connect to a running kernel: ::

    ipyk.py -c 0

Terminate a running kernel: ::

    ipyk.py -k 0

License
-------
This software is licensed under the
`BSD License <http://www.opensource.org/licenses/bsd-license>`_.
See the included LICENSE.rst file for more information.

#Most-Pixels-Ever Python Server

A MPE 2.0 server written in Python.

Most Pixels Ever is a framework that synchronizes frame-based applications across 
multiple screens. Read more about the project: https://github.com/shiffman/Most-Pixels-Ever

###Example Usage:

`$ python mpe-python-server/mpe_server.py`

###Optional Arguments:

    -h, --help            show this help message and exit
    --screens SCREENS     The number of clients. The server won't start the draw
                          loop until all of the clients are connected.
    --port PORT_NUM       The port number that the clients connect to.
    --framerate FRAMERATE
                          The target framerate.

###Requirements:

The MPE Python server is compatible with Python 2.7 and 3.3. Additionally you must install the following modules:

#####Zope.interface

This module may be required to install the Twisted module (below).  
Download here: https://pypi.python.org/pypi/zope.interface/4.0.5

    $ cd zope.interface-4.0.5

Python 2.7:    

    $ python setup.py install

Python 3:    

    $ python3 setup.py install

#####Twisted internet

Python 2.7:  

    $ sudo easy_install twisted

Python 3.3:  

    $ svn checkout svn://svn.twistedmatrix.com/svn/Twisted/tags/releases/twisted-13.1.0
    $ python3.3 setup3.py install  


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


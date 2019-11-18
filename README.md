# ssh-proxy
Python 3 port of Black Hat Python's SSH proxy server

## Installation
Install the dependencies with `pip install -r requirements.txt`. This can also
be done within the virtual environment by running `source venv/bin/activate` first.

## Running
By default, the server will bind to port 8080 on 127.0.0.1. Run the server with
`python ssh-proxy.py -verbose -r {remote_address} -a -u {username}`. 
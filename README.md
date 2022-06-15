# snakeSocks
SOCKS Proxy Port Scanner

## Usage
usage: snake_socks.py [-h] -sh IP Address -sp Port -t TARGET -p TARGETPORTS

optional arguments:
  -h, --help            show this help message and exit
  -sh IP Address, --socks-host IP Address
                        Host to use as the SOCKS Proxy
  -sp Port, --socks-port Port
                        Port to use on the SOCKS Proxy
  -t TARGET, --target TARGET
                        Can be a single IP, or CIDR
  -p TARGETPORTS, --ports TARGETPORTS
                        Can be a single port, top (1000), or all

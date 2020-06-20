# Simple Tor

Simple Rust application to demonstrate usage of libtor to embed a Tor
instance in a Rust binary.

Currently only initialises Tor, nothing else.

### TODO

1. Act as a client: connect to a well known hidden service i.e., do a
   HTTP request to an onion addressed web page.

2. Act as a server:
   - Expose a hidden service
   - Start a simple webserver
   - Test using Tor browser


ref:

Rust libtor: https://github.com/MagicalBitcoin/libtor
C libtor: https://github.com/libtor/libtor

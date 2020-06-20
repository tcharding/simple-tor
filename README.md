# Simple Tor

Simple Rust application to demonstrate usage of libtor to embed a Tor
instance in a Rust binary.

Currently only initialises Tor, nothing else.

### TODO

1. Act as a client:
   - Connect to an onion service i.e., do a HTTP request.

2. Act as a server:
   - Expose a hidden service
   - Start a simple web server
   - Test using Tor browser


ref:

- Rust libtor: [github.com/MagicalBitcoin/libtor](https://github.com/MagicalBitcoin/libtor)
- C libtor: [github.com/libtor/libtor](https://github.com/libtor/libtor)

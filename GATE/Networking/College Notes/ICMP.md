- used as error-correcting mechanism and for host & management queries
- encapsulated in IP datagrams
- ICMP messages:
  - error-reporting messages -> reports problems that a router or a host may encounter
  - query messages -> gets specific information from a router or another host

- 8 byte header and variable-size data section

- ICMP doesn't correct errors, just checks them and reports to original source
  Errors: 
  - destination unreachable
  - source quench
  - time exceeded
  - parameter problem
  - redirection



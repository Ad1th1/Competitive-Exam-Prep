# ARP
  > Intro\
    - Address Resolution Protocol\
    - maps IP address into physical(MAC) addresses\
    - helps exchange MAC addresses\
    - MAC address = 48 bits in hex= usually not changed\
    - port address -> IP address -> MAC address\
    - resolves IPv4 addresses to MAC addresses\
    - maintains a table of mapping
  
  > Working
    - ARP request with destination IP address -> broadcast to everyone(if not present in the table)
    - ARP reply -> unique -> only destination IP address machine will reply
    - ARP request ignored by all others but the one whose IP address matches 
    
    - broadcast request if IP address not in table
    - broadcast address: MAC address
    - target machine responds(unicast) with it's physical address
  
  > RARP = Reverse ARP
    - obsolete cnp used by a client computer to request the IPv4 address from a computer network, when all it has available is the link layer
     or hardware address, such as MAC address
    - can be used to find the IP address of host machine
    - rendered obsolete by Bootstrap protocol(BOOTP) and DHCP
    - RARP can't handle subnets, only IP addresses
    - 
    

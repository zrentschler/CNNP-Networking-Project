This was the final project in my CCNP class at Northampton Community College. It includes:

  * High availability internet connectivity and NAT using HSRP and Stateful NAT
  * Multihome BGP connection with 2 egress routers
  * BGP manipulation with route maps to prefer CCNP1A for egress and CCNP1B for ingress using Local_Pref and MED PAs
  * Multiarea OSPF which only redistributes the default route into CCNP3 and 4's EIGRP network, summarized when possible
  * EIGRP and EIGRP stub area configuration
  * Filtering of EIGRP routes redistributed into OSPF using a distribution list on CCNP3
  * DHCP for the OSPF and EIGRP network
  * Filtering with ACLs which
     * only allows SSH connections to local devices from local devices
     * only allows SSH connections to the ISP routers from the local network's BGP IPs
     * stops outside ingress traffic except in the case of BGP traffic, connections established from within the local network and echo replies

![topology](https://i.imgur.com/3vXWCof.png)

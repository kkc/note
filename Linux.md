## Networking

### TCP SO_REUSEPORT
- https://tech.flipkart.com/linux-tcp-so-reuseport-usage-and-implementation-6bfbf642885a
- https://blog.cloudflare.com/perfect-locality-and-three-epic-systemtap-scripts/#header introduce packet locality
- https://stackoverflow.com/questions/14388706/how-do-so-reuseaddr-and-so-reuseport-differ/
- https://domsch.com/linux/lpc2010/Scaling_techniques_for_servers_with_high_connection%20rates.pdf
- https://github.com/jfischoff/reuse-port-example#readme
  There is a downside to SO_REUSEPORT: when the number of sockets bound to a port changes, there is the possibility that packets for a single TCP connection will get routed to two different sockets. 

### Hot Reload
https://www.haproxy.com/blog/truly-seamless-reloads-with-haproxy-no-more-hacks/

## Cgroup
- https://www.redhat.com/sysadmin/cgroups-part-one

## Networking

### TCP SO_REUSEPORT
- https://tech.flipkart.com/linux-tcp-so-reuseport-usage-and-implementation-6bfbf642885a
- https://blog.cloudflare.com/perfect-locality-and-three-epic-systemtap-scripts/#header introduce packet locality
- https://stackoverflow.com/questions/14388706/how-do-so-reuseaddr-and-so-reuseport-differ/
- https://domsch.com/linux/lpc2010/Scaling_techniques_for_servers_with_high_connection%20rates.pdf
- https://github.com/jfischoff/reuse-port-example#readme
  There is a downside to SO_REUSEPORT: when the number of sockets bound to a port changes, there is the possibility that packets for a single TCP connection will get routed to two different sockets. 
- https://stackoverflow.com/questions/45001349/should-we-use-multiple-acceptor-sockets-to-accept-a-large-number-of-connections

### Hot Reload
- https://www.haproxy.com/blog/truly-seamless-reloads-with-haproxy-no-more-hacks/


### Development Skills
- https://medium.com/fcamels-notes/%E5%9C%A8-linux-%E4%B8%8B%E9%96%8B%E7%99%BC-c-c-%E7%9A%84%E6%96%B0%E6%89%8B%E6%8C%87%E5%8D%97-735fcd960b0

### Futex
- https://blog.csdn.net/jianchaolv/article/details/7544316

### Socket takeover
- https://copyconstruct.medium.com/file-descriptor-transfer-over-unix-domain-sockets-dcbbf5b3b6ec

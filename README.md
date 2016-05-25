Dockerized Shorewall Firewall
=============================

Dockerized firewall provided by shorewall. Run as:

    docker run --net=host --privileged cjntaylor/shorewall:latest <ARGS>

  
Recommended arguments are `try <directory>` where `<directory>` is a mounted 
volume containing the shorewall configuration.

# https://www.practical-docker.com

<img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-160.png">

This is the source repository for https://www.practical-docker.com

In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my YouTube Channel with all episodes for more information.

* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

# episode 01: socks5 proxy vs. port forwarding 
[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

Opening and forwarding specific ports per docker container is ok for a few containers, the more ports you open the more it becomes a hasstle and totally not clear which ports map to which container. 

A simple but very effective solution is to use a socks5 proxy. In this episode I will show how to install and use a socks5 proxy and what benefits it brings to use this solution which is that each container can be reached by its internal hostname which is the name of the container.

Docker containers used:
 * [serjs/go-socks5-proxy](https://hub.docker.com/r/serjs/go-socks5-proxy)

# episode 02:  generating dynamic hostnames
In the previous talk [01 - socks5 proxy vs. port forwarding](01 - socks5 proxy vs. port forwarding) I showed how to reach docker containers by their internal hostname but what if you want to expose a docker containter to the outside? In this episode I will show how to generate a externally accessable dynamic hostname for specific containers.

Docker containers used:
 * []()

# episode 03: generate ssl cerificates for docker containers
Now that we can generate dynamic hostnames for docker containers, that opens the road for automatic generation of ssl certificates for those containers. 

Docker containers used:
 * [](traefik)

# episode 04 - how to find the internal dns name of a docker container
In this episode I will show how to get the interal dns name of a docker container which is more than just the name of a container. Nothing fancy but still a handy trick to remember!

Docker containers used:
 * [](traefik)

# About
In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ) for more information.
* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

```
                        __   __            __    
 .-----.----.---.-.----|  |_|__.----.---.-|  |   
 |  _  |   _|  _  |  __|   _|  |  __|  _  |  |   
 |   __|__|_____._|____|____|__|____|___._|__|   
 |__|  .--|  .-----.----|  |--.-----.----.       
       |  _  |  _  |  __|    <|  -__|   _|       
       |_____|_____|____|__|__|_____|__|         
                                          
```

# https://www.practical-docker.com

<a href="https://www.practical-docker.com"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-drop-160.png?raw=true"></a>

This is the source repository for [https://www.practical-docker.com](https://www.practical-docker.com)

In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my YouTube Channel with all episodes for more information.

* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

---

# EP01: socks5 proxy vs. port forwarding

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

Opening and forwarding specific ports per docker container is onl practical for a few containers but the more ports you open the more it becomes a hasstle and it is totally not clear which ports map to which container. 

A simple but very effective solution is to use a socks5 proxy. In this episode I will show how to install and use a socks5 proxy and what benefits it brings to use this solution which is that each container can be reached by its internal hostname which is the name of the container.

I will also show how to use username/password authentication and show how to use this combination in a secure practical way.

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

<div />

# EP02: socks5 proxy with git (gitlab)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

The proxy example in the previous episode can be extended to not only browsers but also for other protocols as well like like git. In this episode I will show how to use git over a ssh/socks proxy

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

<div />

# EP03: socks5 proxy with Kubernetes (kubernetes-sigs/kind)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

What makes this solution even more attractive is the fact that it can be used inside kubernetes as well. In this episode I will show hwo to install the socs5 proxyy via helm and hwo to access the dashboard.

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

<div />

# EP04: generating dynamic hostnames

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

In the previous talk [EP01: socks5 proxy vs. port forwarding](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy) I showed how to reach docker containers by their internal hostname but what if you want to expose a docker containter to the outside? In this episode I will show how to generate a externally accessable dynamic hostname for specific containers.

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

<div />

# EP05: generate ssl cerificates for docker containers

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

Now that we can generate dynamic hostnames for docker containers, that opens the road for automatic generation of ssl certificates for those containers. 

 * http://xip.io
 * http://nip.io
 * http://vcap.me
 * http://localtest.me
 * http://lvh.me
 * http://ngrok
 * http://pseudo.host/

https://nickjanetakis.com/blog/ngrok-lvhme-nipio-a-trilogy-for-local-development-and-testing

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

<div />

# EP06: how to find the internal dns name of a docker container

<a href="http://www.youtube.com/watch?feature=player_embedded&v=6Maq5IyHSuc
" target="_blank"><img align="right" src="http://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" 
alt="yotube" width="300" border="10" /></a>

In this episode I will show how to get the interal dns name of a docker container which is more than just the name of a container. Nothing fancy but still a handy trick to remember!

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

# About

<a href="https://www.practical-docker.com"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-drop-160.png?raw=true"></a>
In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ) for more information.
* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

# logo

```
                        __   __            __    
 .-----.----.---.-.----|  |_|__.----.---.-|  |   
 |  _  |   _|  _  |  __|   _|  |  __|  _  |  |   
 |   __|__|_____._|____|____|__|____|___._|__|   
 |__|  .--|  .-----.----|  |--.-----.----.       
       |  _  |  _  |  __|    <|  -__|   _|       
       |_____|_____|____|__|__|_____|__|         
                                          
```

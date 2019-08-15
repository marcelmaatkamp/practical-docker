# https://www.practical-docker.com
<a href="https://www.practical-docker.com"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-drop-160.png?raw=true"></a>

This is the source repository for [https://www.practical-docker.com](https://www.practical-docker.com)

In these talks I will give practical tips and tricks on how to effectively use Docker as a valuable tool to solve various problems or just use it for fun projects with all kinds of hardware and software! See my YouTube Channel with all episodes for more information.

* [YouTube Channel with all episodes](https://www.youtube.com/channel/UCxp65f-xyu4z1PvmZBKqZGQ)

# EP01: socks5 proxy vs. port forwarding
<div align="left"><a align="right" href="https://www.youtube.com/watch?v=6Maq5IyHSuc"><img src="https://img.youtube.com/vi/6Maq5IyHSuc/0.jpg" alt="youtube"></a></div>

Opening and forwarding specific ports per docker container is onl practical for a few containers but the more ports you open the more it becomes a hasstle and it is totally not clear which ports map to which container. 

<a href="https://hub.docker.com/_/wordpress/"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-wordpress-160.png?raw=true?raw=true"></a>
<a href="https://hub.docker.com/r/ocassio/go-socks5-proxy/"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-socks5-160-drop.png?raw=true"></a>

A simple but very effective solution is to use a socks5 proxy. In this episode I will show how to install and use a socks5 proxy and what benefits it brings to use this solution which is that each container can be reached by its internal hostname which is the name of the container.

I will also show how to use username/password authentication and show how to use this combination in a secure practical way.

Docker containers used:
 * [ocassio/go-socks5-proxy](https://hub.docker.com/r/ocassio/go-socks5-proxy/)

<hr />

# EP02: socks5 proxy with git (gitlab)
<a href="https://hub.docker.com/r/gitlab/gitlab-ce/"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-gitlab-160.png?raw=true?raw=true"></a>
<a href="https://hub.docker.com/r/serjs/go-socks5-proxy"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-socks5-160-drop.png?raw=true"></a>

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

The proxy example in the previous episode can be extended to not only browsers but also for other protocols as well like like git. In this episode I will show how to use git over a ssh/socks proxy

Docker containers used:
 * [ocassio/go-socks5-proxy](https://hub.docker.com/r/ocassio/go-socks5-proxy/)
 * [gitlab/gitlab-ce](https://hub.docker.com/r/gitlab/gitlab-ce/)
 
# EP03: socks5 proxy with Kubernetes (kubernetes-sigs/kind)
<a href="https://hub.docker.com/r/gitlab/gitlab-ce/"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-gitlab-160.png?raw=true?raw=true"></a>
<a href="https://hub.docker.com/r/serjs/go-socks5-proxy"><img align="right" src="https://github.com/kubernetes-sigs/kind/raw/master/logo/logo.png"></a>

[https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy)

What makes this solution even more attractive is the fact that it can be used inside kubernetes as well. In this episode I will show hwo to install the socs5 proxyy via helm and hwo to access the dashboard.

Docker containers used:
 * [ocassio/go-socks5-proxy](https://hub.docker.com/r/ocassio/go-socks5-proxy/)
 * [gitlab/gitlab-ce](https://hub.docker.com/r/gitlab/gitlab-ce/)

# EP04: generating dynamic hostnames
In the previous talk [EP01: socks5 proxy vs. port forwarding](https://github.com/marcelmaatkamp/practical-docker-episode-01-socks5-proxy) I showed how to reach docker containers by their internal hostname but what if you want to expose a docker containter to the outside? In this episode I will show how to generate a externally accessable dynamic hostname for specific containers.

Docker containers used:
 * []()

# EP05: generate ssl cerificates for docker containers
<a href="https://www.practical-docker.com"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-traefik-160-drop.png?raw=true"></a>
<a href="https://www.practical-docker.com"><img align="right" src="https://github.com/marcelmaatkamp/practical-docker/blob/master/images/practical-docker-letsencrypt-160-drop.png?raw=true"></a>
 
Now that we can generate dynamic hostnames for docker containers, that opens the road for automatic generation of ssl certificates for those containers. 

 * http://xip.io
 * http://nip.io
 * http://vcap.me
 * http://localtest.me
 * http://lvh.me
 * http://ngrok
 * http://pseudo.host/

https://nickjanetakis.com/blog/ngrok-lvhme-nipio-a-trilogy-for-local-development-and-testing

Docker containers used:
 * [traefik](https://hub.docker.com/_/traefik)

# EP06: how to find the internal dns name of a docker container
In this episode I will show how to get the interal dns name of a docker container which is more than just the name of a container. Nothing fancy but still a handy trick to remember!

Docker containers used:
 * [traefik](https://hub.docker.com/_/traefik)

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

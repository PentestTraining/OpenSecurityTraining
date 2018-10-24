# Network Scanning


## Intro
After figuring out what assets are connected with the target / scope we want to further establish what services are running on those assets.

DNS / OSINT - Tells what belongs to the organisation
Servers, Services, User accounts etc

With this we want to figure on the assets and infrasture that our OSINT has found what services do we have accessible that we can use in the next stage. 



### Profiling basics

This generally involves port scanning  / profiling services on the target server. 

There are many levels to this: 
A basic test can go from just typing http://subdomain.domain.com or wwww.google.com into your browser and hitting return. IF you get a page load then you know they have a http server running. If it fowards to https then you know that there is a https server at least. 
With the number of ports there are it would take a long time to profile each service with its designated tool in an automated fashion, so there are some techniques to help us.

As a basic thing, checking if a TCP port is open is a good start as that will tell us that there is likely a service running on that port or at least there is a firewall opening and some service will be / has been there. 


# MinecraftServer
## Setup
### Issues 
1. #### Resources
I bought a digitalocean node to host the server on. What I did not know was minecraft's server needed a lot of resources and memory. 
However my node had half a gig of memory and some old intel cpu. So it was pretty much was dead. I decided to host the server on my pc which has a lot of ram 
and a ryzen 5 5600

2. #### Portforwarding and Static ip
To connect to a server you need portforwarding. Portforwading and dyna-dns costed a lot of money. I could've left out dyna dns and just done portforwarding.
I did end up portforwarding but I needed to change the properties every 3 hours because my router's ip changed every 3 hours, I can't keep changing it.
And then it hit me. All this time I had the digital ocean node with me. I could just use `ssh -R 25565:localhost:25565`. YAY problem fixed

3.#### I care for my pc
I can't just keep my pc online 24x7. I care, that is a big issue. 
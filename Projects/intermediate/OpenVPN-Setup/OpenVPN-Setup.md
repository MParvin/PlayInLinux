OpenVPN setup

#### Level : Intermediate

#### About Project
`Distribution` : `Any`

`Requirements` :
```
A Linux server (For OpenVPN server):
    2 network cards
    one card that connected to Internet with Public IP
    another card that connected to local network with 10.10.0.1 IP

One or more clients with IP range 10.10.0.0/24
```

###### Diagram:

![OpenVPN Diagram](./OpenVPN-Setup.jpg?raw=true "OpenVPN Diagram")

##### Note
Instead of using Public IP(Top diagram), You can use 192.168.1.10.

#### What to do
Setup an OpenVPN server to connect from Internet(or outside the network) to local clinets.

###### Tags:
#OpenVPN #linux #Netowrk #VPN

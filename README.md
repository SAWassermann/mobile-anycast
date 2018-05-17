This repository contains the datasets used in our work entitled *Anycast on the Move: A Look at Mobile Anycast Performance*. In this paper, we describe our analysis for K-Root and F-Root DNS. The datasets additionally include experiments for Google DNS. 

- **WIFI.json** contains the anycast measurements carried out while the user was on a WiFi connection  
- **CELL.json** contains the anycast measurements carried out while the user was on a cellular connection

Each line corresponds to one experiment. 

In each experiment, for each of the 3 DNS services, clients launched ping and traceroute measurements towards the DNS server’s anycast address, as well as towards five chosen unicast addresses of the analyzed DNS service determined to be the geographically closest to the client.

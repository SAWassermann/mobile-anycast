This repository contains the datasets used in our work presented in [1]. In this paper, we describe our mobile-anycast analysis for K-Root and F-Root DNS. The datasets additionally include experiments for Google DNS. 

- **WIFI.json** contains the anycast measurements carried out while the user was on a WiFi connection  
- **CELL.json** contains the anycast measurements carried out while the user was on a cellular connection

Each line corresponds to one experiment. 

In each experiment, for each of the 3 DNS services, clients launched ping and traceroute measurements towards the DNS server’s anycast address, as well as towards five chosen unicast addresses of the analyzed DNS service determined to be the geographically closest to the client.

**If you use this dataset, please cite [1]:**

[1] *Anycast on the Move: A Look at Mobile Anycast Performance*  
S. Wassermann, J. P. Rula, F. E. Bustamante, P. Casas  
in Proceedings of the 2nd Network Traffic Measurement and Analysis Conference (TMA), Vienna, Austria, 2018

```
@article{mobile_anycast,
title = "Anycaston the Move: A Look at Mobile Anycast Performance",
author = "Wassermann, {Sarah} and Rula, {John P.} and Bustamante, {Fabian E} and Pedro Casas",
year = "2018",
month = "6",
journal = "Proceedings of the 2nd Network Traffic Measurement and Analysis Conference (TMA)",
}

 ```

# Subnetting

The subnetting technique is used to split network addressess in subnets optmizing the network addressing. In this way, a large network can be split into several samller ones, supporting efficient management of local networks composed of multiple LANs.

## IANA - Internet Assigned Numbers Authority

## Addressing

### IP Classes

An IPv4 address is composed of two parts. The first numbers in the adddress identify the network while the latter numbers specify the specific host. A subnet mask specifies which part of address is the network part and wich part addresses the specific host. 

IPv4 address space is divided into 5 classes

Class A - 000.0.0.0   = 00000000.00000000.00000000.00000000 to 127.255.255.255 = 01111111.11111111.11111111.11111111

Class B - 128.0.0.0 = 10000000.00000000.00000000.00000000 to 191.255.255.255 = 10111111.11111111.11111111.11111111

Class C - 192.0.0.0 = 11000000.00000000.00000000.00000000 to 223.255.255.255 = 11011111.11111111.11111111.11111111

Class D - 124.0.0.0 = 11100000.00000000.00000000.00000000 to 239.255.255.255 = 11101111.11111111.11111111.11111111

Class E - 240.0.0.0 = 11110000.00000000.00000000.00000000 to 255.255.255.255 = 11111111.11111111.11111111.11111111

### CIDR - Classless Inter-Domain Routing

This addressing notation starts with the network address with the appropriated number of zeros at right of address, followed by slash char and by the length of a prefix (mask of bits) that define the size of the network. 

192.168.0.0/24 - 256 addresses - from 192.168.0.0 to 192.168.0.255 

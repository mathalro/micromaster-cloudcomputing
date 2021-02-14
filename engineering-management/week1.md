# TCP - Transmission Control Protocol

**Responsabilities** - creation, reliability of delivery and assembling of packets of data. 

**Reliability** - connections between communication hosts. A host is an application represented by a port number. Packets are created, sequenced, transmitted, acknowledged and retrasmitted (if necessary).

**Avoid packet congestion** - use slide window

# FTP

File Transfer Protocol (FTP) is used when we need to transfer files between clients and servers. The standard FTP does not provide any security layer and the data travels without any cryptography. Because this, emerged some ways to use FTP in a secure way.

**SFTP** - SSH File Transfer Protocol is the FTP Protocol over a SSH layer. The SFTP uses a single channel for commands and data transfering. It is possible to use basic authentication with encrypted user and password. It can also use SSH key for authentication, that works with public and private keys. Se more about public and private keys in [SSH Session](https://github.com/matheus-almeida-rosa/micromaster-cloudcomputing/blob/master/engineering-management/week1.md#ssh). 

**FTPS** - FTP over SSL (Secure Socket Layer). It uses User ID, password and CA Signed Certificate. 

# SSH

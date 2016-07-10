---
layout: post
title: 'HTTP:Basics Part 1'
date: {}
excerpt: A ton of text to test readability with image feature.
feature: 'http://www.vpnanswers.com/wp-content/uploads/2015/05/http.jpg'
comments: true
published: true
---
### Hello friends ,everyone know about HTTP right but still Iam writing this post because of if you know in detail about communication protocols,it helps while doing web application hacking or any hacking related stuff.Ok then here you go…

### First,what is protocol.a protocol is a standard used to define a method of exchanging data over a computer network such as local area network,Internet,Intranet,etc.   

## Below are some familiar protocols listed:

### AppleTalk:
AppleTalk is a proprietary networking protocol used with Apple Macintosh         computers and networking devices to communicate with each other.

### ARP:
Short for Address Resolution Protocol, ARP is a used with the IP for mapping a 32-bit Internet Protocol address to a MAC address that is recognized in the local network.

### BGP:
Short for Border Gateway Protocol, BGP is a network protocol operating on port 179 for exchanging routing information between gateway hosts.

### DHCP: 
Short for Dynamic Host Configuration Protocol,DHCP is a protocol used to assign an IP address to a computer or device that has been connected to anetwork automatically.

### Ethernet: 
Ethernet is a widely used local-area network (LAN)protocol,Ethernet is a fast and reliable network solution that is still widely used today.

### FTP: 
Short for File Transfer Protocol, FTP is the most common way of sending and receiving files between two computers.

### HTTP:
Short for HyperText Transfer Protocol, HTTP is a set of standards that allow users of the World Wide Web to exchange information found on web pages. The standard port for HTTP connections is port 80.

### ICMP:
Short for Internet Control Message Protocol, ICMP is an extension to the Internet Protocol defined by RFC 792 and an error reporting protocol for TCP/IPmessages. Most users are familiar with ICMP from using the Ping command.

### IMAP:
Short for Internet Message Access Protocol, It is a protocol for retrieving e-mail from a server, similar to POP. The secure version of IMAP is called IMAPS, which stands for IMAP over SSL.

### IP:
Short for Internet Protocol address, an IP or IP address is a number used to indicate the location of a computer or other device on a network using TCP/IP.

### IPsec:
Short for IP Security, IPsec is a set of protocols developed by the Internet Engineering Task Force to support the secure exchange of packets at the IP layer.

### IPv4:
Short for Internet Protocol version 4, IPv4 is a network protocol defined in RFC791 that is the primary Internet and Ethernet network transmission.

### IPv6:
Sometimes referred to as IP next generation, IPv6 is short for Internet Protocol version 6 and is a network protocol for Internet and Ethernet network transmission IPv6 includes improvements over IPv4 such as a wider range of Internet addresses, improved routing and autoconfiguration, embeddedencryption, and more. 

### POP:
Short for Post Office Protocol, POP or POP mailis one of the most commonly used protocols used to receive e-mail on many e-mail clients

### PPPoE:
Short for Point-to-Point over Ethernet, PPPoE is defined in RFC 2516 and is commonly used with cable, DSL, etc. to connect to the Internet using the PPP and Ethernet protocols.

### PPP:
Short for Point-to-Point Protocol, PPP is a communication protocol that enables a user to utilize their dial-up connection (commonly a modem) to connect to other network protocols likeTCP/IP and IPX.

### SMTP:
Short for Simple Mail Transfer Protocol, SMTP is an Internet standard for the sending of e-mail messages over port 25. While it is mostly used for transfer from one mail server to another

### SNMP:
Short for Simple Network Management Protocol,  SNMP examines and changes configuration parameters of LAN and WAN connected repeaters, bridges, routers,switches, and other devices connected to a network.

### SOAP:
Originally short for Simple Object Access Protocol, SOAP is a protocol for exchanging XML messages over a network.

### Socks:
Socks is a protocol for handling client to server requests and communications made through a proxy server.

### SSH:
Short for Secure Shell, SSH (developed by SSH Communications Security Ltd.) is a secure protocol for remote logins. Using an SSH client, a user can connect to a server to transfer information in a more secure manner than other methods, such as telnet.

### TFTP:
Short for Trivial File Transfer Protocol, TFTP is simple file transfer protocol similar to FTP. load files to network devices such as routers.

### TCP/IP:
Short for Transmission Control Protocol/Internet Protocol,TCP/IP is a set of rules (protocols) governing communications among all computers on the Internet.More specifically,TCP/IP dictates how information should be packaged (turned into bundles of information called packets),sent,and received,as well as how to get to its destination.

### UDP:
Short for User Datagram Protocol and defined in RFC 768,UDP is an alternative protocol to the TCP/IP that runs on top of IP and is sometimes referred to as UDP/IP. Unlike TCP/IP,UDP does not divide each transmission into packets, which allows for a faster transmission.However,UDP does not provide error checking.

### VOIP:
Alternatively referred to as IP telephone orInternet phone,VoIP is short for Voice over Internet Protocol, and it enables users to make calls over the Internet.

### So iam not going to explain all the above protocols because our topic is http.

HTTP(hyper text transport protocol)is the underlying protocol used by the World Wide Web.HTTP defines how messages are formatted and transmitted,and what actions Web servers and browsers should take in response to various commands.For example,when you enter a URL in your browser,this actually sends an HTTP command to the Web server directing it to fetch and transmit the requested Web page.Http uses port 80 to transfer its information.below the overview of HTTP protocol.

![p4.png]({{site.baseurl}}/_posts/p4.png)

For example here simple request and response of web site with curl.curl is an open source command line tool and library for transferring data with URL syntax.

### Syntax: curl –v openhackz.in 80

![p1.png]({{site.baseurl}}/_posts/p1.png)

## Versions of HTTP:

### There are mainly three versions are available http/1.0,1.1 and latest http/2.

### 1.Http/1.0: 
In HTTP 1.0 you had to open a new connection for each request/response pair.And after each response the connection would be closed.

## example:
Here iam doing with netcat tool.Netcat is a simple Unix utility which reads and writes data across network connections, using TCP or UDP protocol.It is designed to be a reliable "back-end" tool that can be used directly or easily driven by other programs and scripts.

### nc www.google.com 80
### GET /HTTP/1.0
### Host: www.google.com

![p2.png]({{site.baseurl}}/_posts/p2.png)

you can abserve in above when we request with HTTP/1.0 the connection got disconnected that means again we have to do fresh request.

### 2.HTTP/1.1:
HTTP 1.1 allows you to have persistent connections which means that you can have more than one request/response on the same HTTP connection.

### nc www.google.com 80
### GET /HTTP/1.1
### Host: www.google.com

![p3.png]({{site.baseurl}}/_posts/p3.png)

From the above when we request with HTTP/1.1 the connection still exist in the same connection.

### 3.HTTP/2:
This specification describes an optimized expression of the semantics of the Hypertext Transfer Protocol (HTTP),referred to as HTTP version 2 (HTTP/2).HTTP/2 enables a more efficient use of network resources and a reduced perception of latency by introducing header field compression and allowing multiple concurrent exchanges on the same connection.It also introduces unsolicited push of representations from servers to clients.

### HTTPS:
Short for Hypertext Transfer Protocol Secure,HTTPS is a protocol which uses HTTP on a connection encrypted by transport-layer security.HTTPS is used to protect transmitted data from eavesdropping. It is the default protocol for conducting financial transactions on the web,and can protect a website's users from censorship by a government or an ISP.
-HTTPS uses port 443 to transfer its information.
-HTTPS is first used in HTTP/1.1 and is defined in RFC 2616.





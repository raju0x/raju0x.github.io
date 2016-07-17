---
layout: post
title: 'HTTP:Basics Part 1'
date: 2016-07-17
excerpt: >-
  Short for Hyper Text Transport Protocol. If you want to know more other than acronym then Read More !!
feature: 'http://www.vpnanswers.com/wp-content/uploads/2015/05/http.jpg'
comments: true
published: true
---

### Hello friends,everyone know about HTTP right but still Iam writing this post because of if you good at basics it helps to understand further security issues.Ok then here you go…

First, what is **protocol**. a protocol is a standard used to define a method of exchanging data over a computer network such as local area network, Internet, Intranet,etc.   

In the standard model known as Open Systems Interconnection (OSI), there are one or more protocols at each layer in the communication exchange. OSI is a network model developed by ISO in1978 where peer-to-peer communications are divided into seven layers. Each layer performs a specific task.

![p5.png]({{site.baseurl}}/assets/img/p5.png)

## 1-Physical layer : 

Responsible for transmitting row bit stream over the physical cable. Below are some protocols which belongs to physical layer.

**Ethernet physical layer :** The Ethernet physical layer is the physical layer component of the Ethernet family of computer network standards.

**Bluetooth :** Bluetooth is a wireless technology standard for exchanging data over short distances

**USB :** short for Universal Serial Bus, is an industry standard developed in the mid-1990s that defines the cables, connectors and communications protocols used in a bus for connection, communication, and power supply between computers and electronic devices.

## 2-Data link layer :

Also known as the link layer is responsible for transmitting data across a link.

**Ethernet :** Ethernet is a widely used local-area network (LAN)protocol,Ethernet is a fast and reliable network solution that is still widely used today.

**Token ring :** Token ring a protocol developed by IBM; the name can also be used to describe the token passing ring logical topology that it popularized.

## 3-Network layer :

Responsible for routing information through the network and allowing systems to communicate. The protocols that work in this is layer are :

**Routed Protocols :** Routed protocols used to carry user data between hosts. Below some routed protocols listed.

**AppleTalk :** AppleTalk is a proprietary networking protocol used with Apple Macintosh computers and networking devices to communicate with each other.

**IP :** Short for Internet Protocol address, an IP or IP address is a number used to indicate the location of a computer or other device on a network using TCP/IP.

**IPv4 :** Short for Internet Protocol version 4, IPv4 is a network protocol defined in RFC791 that is the primary Internet and Ethernet network transmission.

**IPv6 :** Sometimes referred to as IP next generation, IPv6 is short for Internet Protocol version 6 and is a network protocol for Internet and Ethernet network transmission IPv6 includes improvements over IPv4 such as a wider range of Internet addresses, improved routing and autoconfiguration, embedded encryption, and more. 

**IPsec :** Short for IP Security, IPsec is a set of protocols developed by the Internet Engineering Task Force to support the secure exchange of packets at the IP layer.

**ICMP :** Short for Internet Control Message Protocol, ICMP is an extension to the Internet Protocol defined by RFC 792 and an error reporting protocol for TCP/IPmessages. Most users are familiar with ICMP from using the Ping command.

**ARP :** Short for Address Resolution Protocol, ARP is a used with the IP for mapping a 32-bit Internet Protocol address to a MAC address that is recognized in the local network.

**Routing Protocols :** Routing protocols performs path determination (routing).Some routing protocols are :

**RIP :** The Routing Information Protocol (RIP) defines a way for routers, which connect networks using the Internet Protocol (IP), to share information about how to route traffic among networks.

**OSPF :** Routers connect networks using the Internet Protocol (IP), and OSPF(Open Shortest Path First)is a router protocol used to find the best path for packets as they pass through a set of connected networks.

**EIGRP :** EIGRP (Enhanced Interior Gateway Routing Protocol) is a network protocol that letsrouters exchange information more efficiently than with earlier network protocols. 

## 4-Transport layer:

Responsible for transferring information between endpoints on the network and deals with errors such as lost or duplicate packets. Find below layer 4 protocols.

**TCP/IP :** Short for Transmission Control Protocol/Internet Protocol, TCP/IP is a set of rules (protocols) governing communications among all computers on the Internet. More specifically,TCP/IP dictates how information should be packaged (turned into bundles of information called packets), sent, and received, as well as how to get to its destination.

**UDP :** Short for User Datagram Protocol and defined in RFC 768, UDP is an alternative protocol to the TCP/IP that runs on top of IP and is sometimes referred to as UDP/IP.Unlike TCP/IP, UDP does not divide each transmission into packets, which allows for a faster transmission.However, UDP does not provide error checking.

## 5-Session layer :

Responsible for managing a session between two applications.

**Socks :** Socks is a protocol for handling client to server requests and communications made through a proxy server. Server Message Block (SMB), one version of which was also known as Common Internet File System (CIFS) operates as an application-layer network protocol  mainly used for providing shared access to files, printers, and serial ports and miscellaneous communications between nodes on a network.

## 6-Presentation layer :

Responsible for the data formatting and display, allowing for compatibility.

**TLS :** Transport Layer Security (TLS) and its predecessor, Secure Sockets Layer (SSL), both of which are frequently referred to as 'SSL', are cryptographic protocols that provide communications security over a computer network. Several versions of the protocols are in widespread use in applications such as web browsing, email, Internet faxing, instant messaging, and voice-over-IP(VoIP). Major web sites use TLS to secure all communications between their servers and web browsers.

## 7-Application layer :

Responsible for user interaction. Below are the appliction layer protocols.

**BGP :** Short for Border Gateway Protocol, BGP is a network protocol operating on port 179 for exchanging routing information between gateway hosts.

**DHCP :** Short for Dynamic Host Configuration Protocol, DHCP is a protocol used to assign an IP address to a computer or device that has been connected to anetwork automatically.

**FTP :** Short for File Transfer Protocol, FTP is the most common way of sending and receiving files between two computers.

**HTTP :** Short for HyperText Transfer Protocol, HTTP is a set of standards that allow users of the World Wide Web to exchange information found on web pages. The standard port for HTTP connections is port 80.

**IMAP :** Short for Internet Message Access Protocol, It is a protocol for retrieving e-mail from a server, similar to POP. The secure version of IMAP is called IMAPS, which stands for IMAP over SSL.

**POP :** Short for Post Office Protocol, POP or POP mailis one of the most commonly used protocols used to receive e-mail on many e-mail clients.

**PPPoE :** Short for Point-to-Point over Ethernet, PPPoE is defined in RFC 2516 and is commonly used with cable, DSL, etc. to connect to the Internet using the PPP and Ethernet protocols.

**PPP :** Short for Point-to-Point Protocol, PPP is a communication protocol that enables a user to utilize their dial-up connection (commonly a modem) to connect to other network protocols likeTCP/IP and IPX.

**SMTP :** Short for Simple Mail Transfer Protocol, SMTP is an Internet standard for the sending of e-mail messages over port 25. While it is mostly used for transfer from one mail server to another

**SNMP :** Short for Simple Network Management Protocol, SNMP examines and changes configuration parameters of LAN and WAN connected repeaters, bridges, routers, switches, and other devices connected to a network.

**SOAP :** Originally short for Simple Object Access Protocol, SOAP is a protocol for exchanging XML messages over a network.

**SSH :** Short for Secure Shell, SSH (developed by SSH Communications Security Ltd.) is a secure protocol for remote logins. Using an SSH client, a user can connect to a server to transfer information in a more secure manner than other methods, such as telnet.

**TFTP :** Short for Trivial File Transfer Protocol, TFTP is simple file transfer protocol similar to FTP. load files to network devices such as routers.

### So iam not going to explain all the above protocols because our topic is http.

## HTTP :

HTTP(hyper text transport protocol)is the underlying protocol used by the World Wide Web. HTTP defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands. For example, when you enter a URL in your browser, this actually sends an HTTP command to the Web server directing it to fetch and transmit the requested Web page.Http uses port 80 to transfer its information. Below the overview of HTTP protocol.

![p4.png]({{site.baseurl}}/assets/img/p4.png)

For example here simple request and response of web site with **curl**. curl is an open source command line tool and library for transferring data with URL syntax.

### Syntax : curl –v example.com 80

![np1.png]({{site.baseurl}}/assets/img/np1.png)

## Versions of HTTP :

### There are mainly three versions are available, HTTP/1.0, 1.1 and latest HTTP/2.

### 1.HTTP/1.0 : 

In HTTP 1.0 you had to open a new connection for each request/response pair. And after each response the connection would be closed.

**Example :**
Here iam doing with **Netcat** tool. Netcat is a simple Unix utility which reads and writes data across network connections, using TCP or UDP protocol. It is designed to be a reliable "back-end" tool that can be used directly or easily driven by other programs and scripts.

### Syntax :

**nc www.example.com 80**

**GET /HTTP/1.0**

**Host: www.example.com**

When ever we request for the resources with particular HTTP version it may or may not gives the content. In my case the target given the content with 200 status code.

![np2.png]({{site.baseurl}}/assets/img/np2.png)

![np2-2.png]({{site.baseurl}}/assets/img/np2-2.png)

you can observe from the above when we request with HTTP/1.0 the connection got disconnected that means again we have to do fresh request.

### 2.HTTP/1.1:
HTTP 1.1 allows you to have persistent connections which means that you can have more than one request/response on the same HTTP connection. Find below eaxample for HTTP/1.1.

### Syntax :

**nc www.example.com 80**

**GET / HTTP/1.1**

**HOST: www.example.com**

After this execution we fetch the requested resources. But relies on the same TCP connection(it won't disconnects from server) then we make another multiple requests.

![np3.png]({{site.baseurl}}/assets/img/np3.png)

![np3-3.png]({{site.baseurl}}/assets/img/np3-3.png)

From the above when we request with HTTP/1.1 the connection still exist in the same HTTP connection.

**Note :** If you want disconnect from one request in HTTP/1.1 then mention **Connection : close**

**Syntax :**
**nc www.example.com 80**
**GET / HTTP/1.1**
**HOST: www.example.com
**Connection : close**

After this execution it disconnects from the server same as HTTP/1.0.

![np4.png]({{site.baseurl}}/assets/img/np4.png)

![np4-4.png]({{site.baseurl}}/assets/img/np4-4.png)

Observe above it disconneted from server

**3.HTTP/2 :**
This specification describes an optimized expression of the semantics of the Hypertext Transfer Protocol (HTTP), referred to as HTTP version 2(HTTP/2). HTTP/2 enables a more efficient use of network resources and a reduced perception of latency by introducing header field compression and allowing multiple concurrent exchanges on the same connection. It also introduces unsolicited push of representations from servers to clients.

**HTTPS :**
Short for Hypertext Transfer Protocol Secure, HTTPS is a protocol which uses HTTP on a connection encrypted by transport-layer security. HTTPS is used to protect transmitted data from eavesdropping. It is the default protocol for conducting financial transactions on the web, and can protect a website's users from censorship by a government or an ISP. HTTPS uses port 443 to transfer its information.

### This is not complete info about HTTP, you can find more about like HTTP methods, HTTP headers, cookies in the next post.


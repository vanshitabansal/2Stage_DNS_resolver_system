# 2Stage-DNS-Resolver-System
Course Project for CS558 
-----------------------------------------------------------------------------------------------------------
Problem Statement:

In this application, you require implementing three C++ programs, namely Client, Proxy Server
(which will act both as client and server) and DNS Server, and they communicate with each other
based on TCP sockets. The aim is to implement a simple 2 stage DNS Resolver System.

List of files submitted:

• dnsCllient.cpp : contains client executable code

• dnsServer.cpp : contains server executable code

• proxyServer.cpp : contains proxy server executable code

• Report.docx : report of submission

• allheaders.h : contains header files used

• proxy_cache.txt : contains proxy cache

• database_mappings.txt : contains dns mappings

To Run:

1. Run DNS Server File providing the port in command line.
2. Run Proxy Server with port in command line
3. Run Client with IP and Port of Proxy Server.
4. Use interactive menu of client to make a request of different type.
5. To change IP of Server used, use “allHeaders.h” file and make necessary changes.

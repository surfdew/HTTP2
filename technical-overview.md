# Technical Overview of HTTP


* HTTP is an application layer protocol. It is currently the highest level of protocol abstraction in the modern networking stack.  
* Application layer protocols define a set of application programming interfaces that can be used to create host applications.
* Example Application Layers:
  - SMTP (Simple Mail Transfer Protocol) - Sending email messages
  - DNS (Domain Name Servers) - Translates Domain names to IP addresses
  - SIP (Session Initiation Protocol) - IP Telephony services like Google or Skype

* There are [two primary models](http://www.tcpipguide.com/free/diagrams/tcpiplayers.png) for network protocol layering.

* Elements of the HTTP API
  * Methods:
    * GET, PUT, POST, DELETE, OPTIONS, etc...
  * Headers:
    * Accept, Cache-Control, Content-Type, Last-Modified, Content-Length
  * Status Codes:
    * 200 OK, 404 NOT FOUND, 401 UNAUTHORIZED

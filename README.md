# Data-Communication-Project-1
Description:

This project introduces the concept of client/server architecture and caching. It is an implementation of a simple web and proxy server that stores and retrieves key-value pairs using socket programming interface. The server only permits commands such as GET PUT and DUMP in the request field followed by the key and value stored.

Commands: 

GET -> returns the value of the key specified
PUT -> stores the key and a specified value on the server
DUMP -> returns lists all of the key value pairs contained in the server

Files:

library.py -> A set of libraries that are useful to both the proxy and regular servers
server.py -> A server to store and retrieve key/value pairs using a socket interface
proxy.py -> A proxy server that forwards requests from one port to another server

Connecting to the Server via a Client: 

1) Install  telnet 
2) Ensure that your server/proxy server program is running on separate terminals
3) Open a terminal and connect to the client using the command  telnet <ip address> <port #>  


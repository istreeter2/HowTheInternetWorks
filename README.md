# The Internet & Linux

The internet is a network of computers interconnected to provide easy access to information to other machines connected to the network

## IP Address - Internet Protocol Address

In this network of computers every individual machine has a unique network address defined by the internet protocol. Currently there are two simultaneous version of the protocol

### IPv4

xxx.xxx.xxx

### IPv6

xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx

## DNS - Domain Name System

When a computer tries accessing google.com for the first time, the machine must query the DNS to get the IP address of Google's web server.

mail.google.com -> .com -> .google -> .mail -> 172.217.3.101

## TLD - Top Level Domain

The domain `.com` is an example of a top level domain. These include `.net` `.org` `.edu` and `.gov`. These TLDs are licensed to organizations by ICANN.

## HTTP/S - Hyper Text Protocols

Simply gettting the IP adress of a web server is not enough for the server to respond with a web page. This is why the http protocol was defined.

### HTTP

A http request will query for a webpage from port 80 (:80) of a web server

### HTTPS

This protocol is identical to HTTP but includes an added layer of TLS/SSL encryption on port 443 between the server and client, making it more secure.

## REST

The REST application paradigm is simply the recomended means of transporting information between client and servers using the defined HTTP methods. Most modern APIs use this paradigm.

### Core methods

`GET: Requests a resource`

`POST: Pushes information to the server`

### Less common methods

`PUT: Uploads a resource`

`PATCH: Updates a resource`

`DELETE: Deletes a resource`

## Linux terminal commands

`rm {file}` deletes `{file}`

`ls` lists files in the current directory

`cp {file} {new file}` copies `{file}` to `{new file}`

`mv {file} {new file}` renames `{file}` to `{new file}`

`cd {directory}` changes the current directory to `{directory}` (using `..` moves up the directory)
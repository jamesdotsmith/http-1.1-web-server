# HTTP/1.1 Web Server
* Web server for processing HTTP/1.0 and HTTP/1.1 requests
* Written in C, built with Makefile

## Usage
### Compiling
1. In terminal, `cd` to project root
2. Compile with `$ make`
3. `$ make clean` for cleaning the project directory

### Example
* With the project compiled, from the project root start the server with `./server`
* Once running, requests can now be made to the server:
```
$ telnet {hostname} 4077
  GET {filename} HTTP/1.1
  Host: {hostname}
  Expect: 100-continue  
```
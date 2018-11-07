# socks5
simple socket5 server

compile:  g++ -o socks5 socks5.cpp -lpthread

By default it only accepts authenticated connections, using the USERNAME define as username, and the PASSWORD define as password. If you want to allow unauthenticated connection requests, add a -DALLOW_NO_AUTH flag when compiling.

The proxy server listens on port 5555, you might as well want to change the SERVER_PORT define if you want it to wait for connections on another port.

tkx , copy from https://raw.githubusercontent.com/mfontanini/Programs-Scripts/master/socks5/socks5.cpp  

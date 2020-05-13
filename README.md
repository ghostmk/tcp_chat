# tcp_chat
Compile both the files with:
```
gcc server.c -o server -lpthread
gcc client.c -o client -lpthread
```
First run the server and specify a port as an argument e.g. 8080
```
./server 8080
```
Then run the client and specify the IP Address of the server and the port as the argument, if server running locally give localhost as IP i.e. 127.0.0.1
```
./client 127.0.0.1 8080
```

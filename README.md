# WebSockets
WebSockets provide a persistent connection between a client and server that both parties can use to start sending data at any time.

After making an intial HTTP request, the client can make a WS request, which remains open so that data can be pushed back and forth. 

The advantage here is that you can send data in either direction without having to include an entire HTTP request every time. No head and cookies. Those can start adding up if you're sending a lot of data back and forth. 

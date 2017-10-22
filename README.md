# Java Chat application
## With broadcast, unicast and blockcast
### (Computer Networks Project)

This is a java based chat application deveolped to broadcast, unicast and blockcast text messages to and from multiple connected clients.
A centrailzed server is responsible for handling all connection requests and forwarding it to the respective clients.

To run, compile and run Server.java on the respective environment.
For each client, compile and run an instance of Client.java on the respective environment.
For every client instance running, its registration is automatically handled by the server and broadcasted.
Using the ID provided by the server, clients can communicate amongst themeselves.

To send a message:

`cast_type data_type client_number data`

e.g. -
```
	broadcast message "Hello World"
	unicast message 2 "Greetings Client 2"
	blockcast message 5 "Welcome all, except 5 :p"
```

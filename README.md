# TCPTextCommunicator

TCP text communicator made in C++ on server side and Java on client side. Made for computer networks on studies in Poznan University of Technology.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

What things you need to install the software

```
1. Linux OS
2. gcc compiler
```

### Installing

A step by step series of examples that tell you how to get a development env running

Clone project or download .zip

```
git clone https://github.com/Pefes/TCPTextCommunicator.git
```

Go into ./TCPTextCommunicator/ggServer

```
cd ./TCPTextCommunicator/ggServer
```

Compile the server program with command:

```
g++ -Wall -pthread main.cpp src/models/Server.cpp src/models/Message.cpp src/models/User.cpp -o main
```

Run the server with one argument of server port, default = 1234

```
./main [server port]
```

Go back to main directory

```
cd ..
```

Run client program

```
./ggClient/out/arifacts/ggClient/ggClient.jar
```

## Built With
* [socket.h](http://man7.org/linux/man-pages/man2/socket.2.html) - Library to create sockets and maintain TCP connection
* [pthread.h](http://man7.org/linux/man-pages/man7/pthreads.7.html) - Library to manage multithreaded server
* [JavaFX](https://docs.oracle.com/javafx/2/) - Graphics library
* [Maven](https://maven.apache.org/) - Dependency Management

## Authors

* [Pefes](https://github.com/Pefes) - *server side program*
* [TheTerabit](https://github.com/TheTerabit) - *client side program*

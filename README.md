# SIMPLE JAVA WEB SERVER
This project implements a client-server application using Java's socket programming, featuring three implementations: single-threaded, multi-threaded, and thread-pooled. The repository includes server and client code for each approach, demonstrating different strategies for handling client connections. Additionally, JMeter was used to perform load testing to evaluate the performance and capacity of all implementations under varying loads.
## Features
-Single-threaded Implementation: Handles one client connection at a time, suitable for simple testing or low-load scenarios.
-Multi-threaded Implementation: Handles multiple client connections concurrently by spawning a new thread for each client.
-Thread-pooled Implementation: Uses a fixed-size thread pool to manage client connections efficiently, balancing performance and resource usage.
-Socket-based Communication: Uses Java's ServerSocket and Socket classes for TCP communication.
-Basic Message Exchange: Demonstrates text-based communication between client and server.
-Load Testing: JMeter was used to simulate multiple client requests and assess the load-bearing capacity of all server implementations.
## Prerequisites
- JAVA development kit(JDK) 8 or higher
- A JAVA IDE or command-line environment to compile and run the code
- Apache jmeter(for load testing)
## How to Run
1.**Clone the Repository**
```bash
git clone https://github.com/r-ishabh12/WebServer.git
```
For Single-Threaded Version
2.** Navigate to the single Threaded directory**
```bash
cd SingleTHreaded
```
3.**Complie the Java files**
```bash
javac Server.java
javac Client.java
```
4.**Start Server & Client**
```bash
java Server
java Client
```
## Screenshot

For Multi-Threaded Version
2.** Navigate to the Multi Threaded directory**
```bash
cd MultiThreaded/src
```
3.**Complie the Java files**
```bash
javac Server.java
javac Client.java
```
4.**Start Server & Client**
```bash
java Server
java Client
```
For Thread Pool
2.** Navigate to the Thread Pool directory**
```bash
cd ThreadPool/src
```
3.**Complie the Java files**
```bash
javac Server.java
javac Client.java
```
4.**Start Server & Client**
```bash
java Server
java Client
```



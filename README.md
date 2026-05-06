# chat-Messanger-with-Log-Facility
A real-time chat application using TCP sockets with timestamp-based message logging functionality.

## Project Overview
Chat Messenger with Log Facility is a simple client-server based chatting application developed using Java Socket Programming. The project demonstrates real-time communication between a server and a client over a network using TCP sockets.

This application allows:
- Two-way communication between client and server
- Continuous message exchange using loops
- Console-based chatting interface
- Basic logging and communication handling

The project is useful for understanding:
- Java Networking
- Socket Programming
- Client-Server Architecture
- Input/Output Streams
- Real-time communication concepts

---

# Features
- Real-time chat between client and server
- Server waits for incoming client connections
- Continuous communication until client exits
- Uses TCP protocol for reliable communication
- Simple and lightweight console application
- Beginner-friendly networking project

---

# Technologies Used
- Java
- Socket Programming
- TCP/IP Networking
- BufferedReader
- PrintStream
- Input/Output Streams

---

# Project Structure

```bash
ChatMessenger/
│
├── ChatServerLoop.java
├── ChatClientLoop.java
└── README.md
```

---

# How It Works

## Server Side
- Creates a `ServerSocket` on port `5100`
- Waits for client connection requests
- Accepts incoming connection
- Reads messages from client
- Sends replies back to client

## Client Side
- Connects to the server using IP and port
- Sends messages to server
- Receives responses from server
- Communication continues until `"end"` is entered

---

# How to Run the Project

## Step 1: Compile the Files

```bash
javac ChatServerLoop.java
javac ChatClientLoop.java
```

---

## Step 2: Start the Server

```bash
java ChatServerLoop
```

Output:

```bash
Server is waiting at port 5100
```

---

## Step 3: Start the Client

Open another terminal and run:

```bash
java ChatClientLoop
```

Output:

```bash
Client gets connected with server successfully
```

---

# Sample Chat

## Client

```bash
Hello Server
```

## Server

```bash
Client says : Hello Server
Enter message for client :
```

## Server Reply

```bash
Hello Client
```

## Client Receives

```bash
Server says : Hello Client
```

---

# Concepts Used

- Client-Server Communication
- Java Networking API
- TCP Socket Connection
- Infinite Communication Loop
- Stream Handling
- Buffered Input/Output
- Exception Handling

---

# Learning Outcomes
Through this project, you can learn:
- How network communication works in Java
- How sockets establish connections
- How data is transmitted between systems
- Basics of real-time messaging applications
- Working with input and output streams

---

# Future Enhancements
- GUI-based chat application using Java Swing/JavaFX
- Multi-client support
- Chat history storage
- File sharing feature
- Encryption for secure communication
- Timestamp-based message logging

---

# Author
Developed by Diksha Vispute as a networking and Java socket programming project.

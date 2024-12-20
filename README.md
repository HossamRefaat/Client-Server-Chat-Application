# Client-Server Chat Application

## Overview
This project is a Java-based Client-Server Chat Application for real-time group communication. It employs socket programming and multi-threading to manage multiple client connections, allowing users to send and receive messages in a shared chat environment.

## Features
- Real-time communication.
- Supports multiple client connections.
- Broadcasts messages to all connected clients.

## Components
1. **Client.java**: Connects to the server, sends user messages, and listens for incoming messages.
2. **ClientHandler.java**: Manages client connections, processes messages, and broadcasts them to other clients.
3. **Server.java**: Accepts client connections and creates threads for communication.

## Prerequisites
- Java Development Kit (JDK).
- Basic knowledge of Java programming.

## How to Run
1. Opent src folder.
2. Open terminal from this folder one for the server and as you want for the clients.
3. Start the server:
   - Run command: `java Server.java`
4. Connect clients:
   - Run command: `java Client.java`
5. Start chatting by typing messages in the client terminal.

## Project Structure
. ├── Client.java ├── ClientHandler.java └── Server.java

## Example Usage
1. Start the server: `java Server`
2. Connect a client: `java Client` (Provide a username when prompted)
3. Chat messages from one client will broadcast to all others.



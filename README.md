# ChatHub: Real-time Group Chat Server

ChatHub is a Java-based group chat server application that enables real-time communication among multiple clients in a group chat. The server utilizes socket programming to establish and manage connections, allowing users to send and receive messages simultaneously.

## Features

- **Group Chat:** Connect multiple clients to the server and participate in group conversations.
- **Real-time Messaging:** Experience instant messaging within the group chat network.
- **Broadcasting:** The server has the ability to broadcast messages to all connected clients, allowing seamless group communication.
- **Java Implementation:** Built with Java.

## Project Structure

### 1. GroupChatServer
   - Main class for the server application.
   - Manages client connections, handles incoming messages, and facilitates broadcasting.

### 2. Client
   - Represents a client connection on the server.
   - Handles individual client communication and messaging.

### 3. GroupChat
   - Client application to connect to the group chat server.
   - Enables users to send and receive messages in the group chat.

### 4. Message
   - Represents a message within the chat system.
   - Used for communication between clients and the server.

## Class Diagram
![projectClassDiagram-removebg-preview-2](https://github.com/vDalken/ChatHub/assets/148246203/5d18d62e-9d01-402c-a29c-15bb9e57cf9a)


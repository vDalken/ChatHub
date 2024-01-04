# Chatify: Real-time Group Chat Server

Chatify is a Java-based group chat server application that enables real-time communication among multiple clients in a group chat environment. The server utilizes socket programming to establish and manage connections, allowing users to send and receive messages simultaneously.

## Features

- **Group Chat:** Connect multiple clients to the server and participate in group conversations.
- **Real-time Messaging:** Experience instant messaging within the group chat network.
- **Broadcasting:** The server has the ability to broadcast messages to all connected clients, fostering seamless group communication.
- **Java Implementation:** Built with Java, ensuring platform independence and ease of deployment.

## Project Structure

### 1. GroupChatServer
   - Main class for the server application.
   - Manages client connections, handles incoming messages, and facilitates broadcasting.

### 2. ClientHandler
   - Represents a client connection on the server.
   - Handles individual client communication and messaging.

### 3. GroupChatClient
   - Client application to connect to the group chat server.
   - Enables users to send and receive messages in the group chat.

### 4. Message
   - Represents a message within the chat system.
   - Used for communication between clients and the server.

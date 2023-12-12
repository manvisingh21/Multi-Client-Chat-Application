Problem Statement: Design and implement a multi-client chat application using Python and socket programming. Create a server that can handle multiple clients concurrently and allows them to exchange messages in real-time. Develop a simple client interface that enables users to send and receive messages through the server. The goal is to simulate a basic chat system where messages from one client are broadcasted to all connected clients.

Key Features:
1. Server Functionality
   - Listen for incoming connections from multiple clients.
   - Maintain a list of connected clients.
   - Implement a broadcast mechanism to send messages from one client to all other clients.

2. Client Functionality
   - Connect to the server and join the chat.
   - Send messages to the server for broadcast.
   - Receive and display messages from other connected clients.

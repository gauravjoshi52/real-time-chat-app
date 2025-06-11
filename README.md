*REAL TIME CHAT APP*:

*COMPANY: CODTECH IT SOLUTIONS

*NAME: GAURAV JOSHI

*INTERN ID: CT08DN128

*DOMAIN: FRONT END DEVELOPMENT

*DURATION: 8 WEEKS

*MENTOR: NEELA SANTOSH

DESCRIPTION: 
A real-time chat application allows users to send and receive messages instantly, making communication seamless and dynamic. In a typical setup using Node.js for the backend and React for the frontend, the app efficiently handles multiple users and real-time interactions.

On the backend, Node.js is ideal because of its non-blocking, event-driven architecture, which makes it excellent for handling I/O operations like messaging. A popular library used for real-time communication is Socket.IO, which enables WebSocket-based communication between the client and server. The server listens for events like user connection, message sending, and disconnection, and broadcasts messages to all connected clients or specific rooms (like group chats).

The React frontend handles the user interface. It listens to events from the server using the client version of Socket.IO and updates the chat UI instantly when a new message is received. React's component-based structure allows for clean management of chat windows, message lists, and user inputs.

Here’s a simplified flow:

A user opens the React app, which connects to the Node.js server via WebSocket.

The server acknowledges the connection and keeps track of active users.

When a message is typed and sent, the client emits a "chat message" event to the server.

The server receives this and broadcasts the message to other connected clients.

React listens for new messages and re-renders the chat view in real-time.

To persist messages or handle authentication, you can integrate a database like MongoDB and tools like JWT (JSON Web Token). This setup forms a scalable and responsive chat system.

This stack—Node.js, React, and Socket.IO—is lightweight yet powerful for building modern, real-time applications.

#OUTPUT:
![Image](https://github.com/user-attachments/assets/d229ca5b-30ed-4a21-b692-3450e959b1c5)

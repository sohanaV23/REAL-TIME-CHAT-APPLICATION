# REAL-TIME-CHAT-APPLICATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* :  VALABOJU SOHANA 

*INTERN ID* : CT06DG1136

*DOMAIN* : FRONT-END WEB DEVELOPMENT

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTHOSH

## Introduction
- A simple real-time chat application built with Node.js, Express, and Socket.IO.
- Enables multiple users to send and receive messages instantly in a shared chat room.
- Lightweight front-end with a clean UI for seamless chatting experience.

## Technologies Used
- **Node.js & Express:** Backend server and static file serving.
- **Socket.IO:** Real-time bidirectional event-based communication.
- **HTML, CSS, JavaScript:** Front-end structure, styling, and client-side socket logic.

## Key Features
- Real-time messaging with instant broadcast to all connected clients.
- User connection and disconnection logging on the server console.
- Responsive and minimalistic chat interface.
- Auto-scrolling message list to show the latest messages.

## How It Works
- Server creates an HTTP server with Express and attaches Socket.IO to it.
- Clients connect via Socket.IO and listen for incoming messages.
- When a user sends a message, it’s emitted to the server, which then broadcasts it to all clients.
- The front-end updates the message list dynamically without page refresh.

## Project Structure
- **server.js:** Sets up Express server and Socket.IO logic.
- **public/**: Contains client-side files:
  - `index.html`: Chat UI markup.
  - `style.css`: Styling for the chat interface.
  - `script.js`: Client-side Socket.IO event handling and DOM manipulation.

## Future Enhancements
- Add user authentication and nickname support.
- Display timestamps and user labels alongside messages.
- Store chat history in a database for persistence.
- Add notifications for user join/leave events.
- Improve UI with better styling and mobile responsiveness.
  
## Output



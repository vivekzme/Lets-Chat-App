# Lets-Chat-App

Let's Chat is a real-time chat application built using Node.js and Socket.IO. It provides users with a seamless and interactive chatting experience, allowing them to engage in conversations with each other in real-time.

- Description: This is a scalable Realtime Chatting Application that allows multiple users to chat simultaneously through a user-friendly interface.

- FrontEnd Technologies:
  - HTML: Used for structuring the application.
  - CSS: Employed for styling the application.
  
- BackEnd Technologies:
  - JavaScript: Used for both client-side and server-side functionality.
  - Node.js: Powers the server-side development.
  
- Socket.io: Utilized to establish a two-way connection between the client and the server, enabling real-time communication.

- FrontEnd Features:
  - Navigation Bar: Provides easy access to different sections of the application.
  - Chat Window: Displays the ongoing conversations between users.
  - Form Submit Button: Allows users to send messages in the chat.
  
- Client-Side JavaScript:
  - Manipulating DOM: Implemented client-side JavaScript to interact with and modify DOM elements.
  - Stored DOM Elements: All necessary DOM elements are stored in respective JavaScript variables.
  
- Audio Notification:
  - Audio File: Included a notification sound file (ting.mp3) to alert users when they receive new messages.
  
- User Interaction:
  - Name Prompt: When a new user joins, they are prompted to enter their name, which is then communicated to the server.
  - Event Listener: Listens for events sent by the server when a new user joins.
  - Message Reception: Utilizes the receive function to receive and display messages sent by other users.
  - User Departure: Notifies all other users when someone leaves the chat.
  
- Server-Side JavaScript:
  - Socket.IO Connections: Handles the Socket.IO connections on the server side.
  - New User Notification: Informs all connected users when a new user joins the chat.
  - Message Broadcasting: Broadcasts messages sent by users to all other connected users.
  - User Departure Notification: Alerts other users when someone leaves the chat.

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

# Process to run the app:

1. Open your terminal or command prompt.
2. Run the command `nodemon nodeserver/index.js` to start the Node.js server using nodemon.
3. Install the 'Live Server' extension for Visual Studio Code. The extension ID is ritwickdey.liveserver.
4. Once the extension is installed, navigate to the index.html file in your project directory.
5. Right-click anywhere in the index.html file and select "Open with Live Server" from the menu.
6. A new instance of the application will open in your default web browser.

To open multiple instances of the app:

7. Copy the URL from the address bar of the browser where the application is running.
8. Open another tab in the same browser or open a different browser (or incognito mode).
9. Paste the copied URL into the address bar of the new tab or browser.
10. Press Enter to open another instance of the application in the new tab or browser.

By following these steps, you can run the app locally and have multiple instances running in different tabs, incognito mode, or different browsers.

<img width="1440" alt="Screenshot 2023-06-21 at 1 55 06 PM" src="https://github.com/vivekzme/Lets-Chat-App/assets/98255913/6fdc6fbb-5d18-4836-b46a-82c726566937">

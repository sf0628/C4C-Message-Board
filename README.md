
This application enables users to exchange messages on a chat board using their chosen usernames. Messages, limited to 128 characters, display the username and timestamp beneath them. It's built with React, Node, HTML, and CSS, where CSS and HTML collaborate to create the board's appearance and functionality.

The Node component utilizes socket.io to communicate with React. It notifies React of message sending, user joining or leaving the chat room. React receives messages from Node, displaying them in chronological order.

Key features include sending limited-length messages, viewing messages in descending order, cross-computer messaging, and the option to select a username displayed with each sent message.

To start the application:

Download and unzip the file from GitHub.
Install Flask (if not already installed) using "pip3 install flask" in the terminal.
Install Node.js from https://nodejs.org/en/download.
Navigate to the server folder and run "npm start" to start the Node server.
In a new terminal, navigate to the client folder and run "npm start" to open the chatroom at http://localhost:3000. Follow the instructions to begin using the chat.

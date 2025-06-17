# task2-CHAT-APPLICATION

COMPANY:CODETECT IT SOLUTIONS

NAME:MANAL RUWAIDA

INTERN ID:CT04DN861

DOMAIN:FULL STACK

DURATION:4 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

DESCRIPTION ON CHAT APPLICATION:
This chat application is a real-time web-based communication tool built using modern web technologies. It enables multiple users to connect, send, and receive messages instantly using WebSockets. The structure of the application involves both front-end and back-end components, each represented by different essential files in the project.

1. index.html – The Web Interface
The index.html file forms the foundation of the front-end user interface. It contains the markup that defines the layout of the chat application. This includes the message input area, chat display window, and buttons to send messages or perform actions. It may also include embedded links to style.css for styling and script.js for dynamic behavior. As a static HTML file, it acts as the main entry point for the user, delivering the initial view and UI components when the page loads in the browser.

2. style.css – Styling and Presentation
The style.css file is responsible for the visual styling of the chat application. It defines how elements such as text boxes, buttons, message bubbles, and chat windows appear. Using CSS, developers can customize fonts, colors, margins, paddings, borders, and animations. A clean, user-friendly design improves the overall usability of the chat application. Responsive CSS can also make the app usable on both desktop and mobile devices.

3. script.js – Client-Side Functionality
script.js provides the front-end logic using JavaScript. It typically handles the interaction between the user and the application, such as capturing typed messages, sending them to the server, and updating the chat window when new messages arrive. It also manages the connection to the server through WebSockets using libraries like Socket.IO. When the user submits a message, the script emits a socket event, and when a new message is received, it updates the DOM in real time.

4. server.js – Back-End Server Logic
The server.js file runs on the server and handles all back-end operations. Built using Node.js and Express.js, it creates an HTTP server and may integrate Socket.IO to support real-time bidirectional communication between clients. It listens for connection events from clients, broadcasts messages to all connected users, and may even handle room logic or usernames. This is the heart of the chat app, ensuring all users see each other's messages in real time.

5. package.json – Project Configuration
The package.json file contains metadata about the project and lists its dependencies. When someone wants to use or contribute to the project, they can install all required packages by running npm install. Common dependencies include express for server functionality and socket.io for real-time communication. The file also defines scripts like npm start, which can launch the server.

6. package-lock.json – Dependency Management
package-lock.json is automatically generated when dependencies are installed. It ensures consistent installation by locking the specific versions of packages and their dependencies. This prevents version mismatches that could break the application across different environments or systems.

OUTPUT:

![Image](https://github.com/user-attachments/assets/ea4a376d-a1e1-42c6-9740-5677cdb05c8e)

![Image](https://github.com/user-attachments/assets/7c9a92a2-73f7-45a5-aa2f-b6a7ade05386)

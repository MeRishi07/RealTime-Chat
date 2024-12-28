# Chat Meet Application

## Overview
Chat Meet Application is a real-time chat application that enables users to communicate through text messages, make video calls, and share screens. The main goal of this project is to provide a seamless and interactive communication platform for users to connect with each other remotely. The application is designed to be easy to use and efficient, ensuring a smooth and enjoyable experience for all users.

![ChatMeet](https://github.com/MeRishi07/RealTime-Chat/blob/2da71f6a81ca85af1984d2350d7507d65510ad75/app-frontend/8e1d99171171704c393e42fd0f1b6cac.jpg)

## Features
- **Real-time Text Messaging:** Users can exchange text messages in real-time, allowing for instant communication and efficient collaboration.

- **Video Call Functionality:** The application provides video call functionality, allowing users to have face-to-face conversations with each other regardless of their physical locations.

- **Screen Sharing Option:** Users can share their screens during video calls, making it convenient for presentations, demonstrations, and collaboration on shared documents.


## Project Details
The Chat Meet Application is built using a combination of powerful technologies and tools, making it a robust and reliable platform for communication. Here are some key details about the project:

- **Secure Authentication:** To ensure the security and privacy of user data, the application uses JSON Web Tokens (JWT) for authentication. This prevents unauthorized access and ensures that only authenticated users can access the chat and video call features.

- **WebSocket Communication:** Real-time text messaging is implemented using WebSocket communication. WebSockets provide a persistent connection between the client and server, enabling instant message delivery without the need for constant polling.

- **WebRTC for Video Calls:** The video call functionality is powered by WebRTC (Web Real-Time Communication), a collection of communication protocols and APIs that enable peer-to-peer communication between users. This technology ensures high-quality video calls with low latency.

## Installation and Setup
To run the Chat Meet Application locally, follow these steps:

### Backend Setup:
1. Clone the repository:
   ```bash
   git clone https://github.com/kalash33/Chat_Meet_App.git
   cd Chat_Meet_App
   ```
2. Navigate to the app-backend folder:
   ```bash
    cd app-backend
    ```
3. Install dependencies and run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
    ```

### Frontend Setup:
1. Navigate to the app-frontend folder:
   ```bash
   cd ../app-frontend
   ```
2. Install dependencies:
   ```bash
    npm install
    ```
3. Start the Angular development server:
    ```bash
    ng serve
    ```
4. Access the application:      
Open your web browser and visit: `http://localhost:4200 `
            
## Technologies Used

The Chat Meet Application is built using the following technologies:

### Frontend:
- Angular: A modern, open-source, and widely-used web application framework for building dynamic and responsive user interfaces.
- WebSockets: Used for real-time communication between the client and server, enabling instant messaging and chat functionality.
- WebRTC: Utilized for video call functionality, enabling peer-to-peer video streaming between users.
- JWT (JSON Web Tokens): Employed for secure user authentication and authorization, ensuring data privacy and access control.

### Backend:
- Java Spring Boot: A powerful and flexible framework for building backend applications, providing essential features like security, REST APIs, and more.
- MongoDB: A NoSQL database used for storing chat messages and user data in a flexible, schema-less format.
- Redis: Used for caching and storing session data, enhancing application performance and scalability.

### Other Tools:
- Git: A version control system for collaborative development and managing code changes.
- GitHub: A web-based platform for hosting and sharing code repositories.
- VSCode: A popular code editor with rich features and extensions for efficient development.


The project aims to provide a seamless and interactive communication platform for users, offering modern features and ensuring data security.

Feel free to explore the source code and contribute to the project on [GitHub](https://github.com/kalash33/Chat_Meet_App).


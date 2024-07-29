# ConnectHub - Real-Time Chat Application

ConnectHub is a real-time chat application that enables seamless communication between users. Built using modern web technologies, it features real-time messaging with Socket.io, user authentication, and a responsive UI designed with Tailwind CSS and Daisy UI.
## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
## Features
- **Real-Time Communication**: Chat with other users instantly using Socket.io.
- **User Authentication**: Secure login/signup with JWT authentication and bcrypt for password hashing.
- **Online Users Tracking**: View a list of users who are currently online.
- **User Search**: Search for users and start conversations easily.
- **Notifications**: Real-time notifications with iOS-style sounds for new messages.<br></br>

## Screenshots
### 1. The Login/SignUp page (User must authenticate)<br></br>
  ![image](https://github.com/user-attachments/assets/949cbedf-6f8c-43a7-bcfa-47fd2500a13c)<br></br>

### 2.The Users who are online and Search Users functionality are integrated in real time with Socket.io along with real time messaging.
### There is also Logout button functionality under the users.<br><br/>
  ![image](https://github.com/user-attachments/assets/3d5b04f4-560b-4d92-bb2b-81e7cfe703ce)<br></br>

###  Note: The profile pictures and the emojees in each user are generated dynamically.
   
## Installation
To set up the application locally, follow these steps:

### Prerequisites
- Node.js
- npm

### Backend Setup
###### 1. Navigate to the backend directory 'cd folder'.
###### 2. Type 'npm i'to install all necessary packages.
###### 3. Run the server by 'npm run server' or 'npm build'.
###### 4. Create a .env file and add your environment variables
####  "PORT=5000
####   MONGO_URI=your_mongodb_uri
####   JWT_SECRET=your_jwt_secret
####   NODE_ENV=development"<br></br>

### Frontend Setup
###### 1. Navigate to the forntend directory 'cd folder'.
###### 2. Type 'npm i'to install all necessary packages.
###### 3 .Type 'npm run dev'.

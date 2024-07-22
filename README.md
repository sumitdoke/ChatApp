# Real-Time Chat Application

## Overview

Welcome to the Real-Time Chat Application, a dynamic platform built on the MERN stack (MongoDB, Express.js, React.js, Node.js). This application enables users to communicate instantly, manage their profiles, and connect with others in real-time.

## Features

- **Real-Time Messaging**: Experience seamless communication with instant message delivery powered by Socket.IO.
- **User Profiles**: Create and manage personalized profiles, including profile pictures and status updates.
- **Online Status Indicator**: Easily see which users are currently online for more engaging interactions.
- **Responsive Design**: Enjoy a consistent and user-friendly experience across all devices, from desktops to mobile phones.
- **User Authentication**: Secure login and signup processes utilizing JWT (JSON Web Tokens) for robust authentication and authorization.
- **Group Chats**: Create and participate in group chats to connect with multiple users simultaneously.
- **Message Notifications**: Receive real-time notifications for new messages, ensuring you never miss an important conversation.
- **Search Functionality**: Quickly find users and messages with an integrated search feature, enhancing navigation and accessibility.

## Tech Stack

- **Frontend**: React.js, Redux for state management, Axios for API calls
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.IO
- **Styling**: CSS, Bootstrap (or any preferred styling framework)

## Installation

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Git (optional)

### Clone the Repository

```bash
git clone https://github.com/yourusername/ChatApp.git
cd ChatApp
```

### Backend Setup

1. Navigate to the backend directory:

```bash
cd Backend
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the `Backend` directory and add your environment variables:

```dotenv
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the backend server:

```bash
npm start
```

### Frontend Setup

1. Navigate to the frontend directory:

```bash
cd ../Frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend application:

```bash
npm start
```

## Usage

- **Sign Up**: Create a new account by providing your details.
- **Login**: Access your account using your credentials.
- **Chat**: Engage in real-time conversations with other users.
- **Profile Management**: View and edit your profile, as well as explore other users' profiles.
- **Online Users**: Check the list of users currently online to enhance your chat experience.
- **Group Chats**: Start or join group chats for collaborative discussions.
- **Search Users and Messages**: Utilize the search feature to find specific users or messages quickly.

## Contributing

We welcome contributions! If you have suggestions for improvements or want to add features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by various real-time chat applications.
- Special thanks to the open-source community for the libraries and tools that made this project possible.

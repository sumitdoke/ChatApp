Real-Time Chat Application

## Overview

This is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). Users can send and receive messages instantly, view profiles of other users, and see who is currently online.

## Features

- **Real-Time Messaging**: Send and receive messages instantly using Socket.IO for seamless communication.
- **User Profiles**: View and manage user profiles, including profile pictures and status updates.
- **Online Status**: See which users are currently online in real-time.
- **Responsive Design**: The application is fully responsive, ensuring a consistent experience across devices.
- **User Authentication**: Secure login and signup functionality using JWT (JSON Web Tokens) for authentication and authorization.

## Tech Stack

- **Frontend**: React.js, Redux for state management, Axios for API calls
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.IO
- **Styling**: CSS, Bootstrap (or any other preferred styling framework)

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
- **Login**: Log in to your account using your credentials.
- **Chat**: Start chatting with other users in real-time.
- **Profile**: View and edit your profile and see other users' profiles.
- **Online Users**: Check the list of users currently online.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by various real-time chat applications.
- Thanks to the open-source community for the libraries and tools that made this project possible.

```


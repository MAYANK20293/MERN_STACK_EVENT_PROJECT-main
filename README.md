# Event Management System (MERN Stack)

## Overview
The Event Management System is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to manage events, schedule tasks, and coordinate with other participants efficiently. The platform provides features such as user authentication, event creation, task management, and real-time collaboration.

## Features
- **User Authentication:** Secure login and registration using JWT authentication.
- **Event Management:** Users can create, update, and delete events.
- **Task Management:** Create tasks within events and assign priorities.
- **Friend Management:** Add friends and collaborate on events.
- **Drag-and-Drop Functionality:** Easily manage tasks with a Kanban board.
- **Real-Time Updates:** WebSocket integration for live updates.

## Technologies Used
### Frontend:
- React.js (with Hooks and Context API)
- Redux (for state management)
- Tailwind CSS (for UI styling)
- Vite for faster development and HMR (Hot Module Replacement)

### Backend:
- Node.js with Express.js
- JWT for authentication
- MongoDB (with Mongoose ODM)
- WebSockets (Socket.io)

## Installation
### Prerequisites:
Ensure you have the following installed:
- Node.js
- MongoDB

### Clone the Repository:
```bash
git clone <repository-url>
cd event-management-system
```

### Backend Setup:
```bash
cd backend
npm install
npm start
```

### Frontend Setup:
```bash
cd frontend
npm install
npm start
```

### Environment Variables:
Create a `.env` file in the backend directory with the following variables:
```plaintext
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your Secret Key>
PORT=5000
```

## Usage
1. Register a new account or log in using existing credentials.
2. Create an event and add tasks.
3. Invite friends to collaborate on the event.
4. Manage tasks using the Kanban board.

## Project Structure
```
.
├── backend
│   ├── controllers
│   ├── database
│   ├── models
│   ├── router
│   ├── app.js
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   └── App.js
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── README.md
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── vite.config.js
│   └── .gitattributes
```

## Contribution
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, contact:
- **Name:** Mayank
- **Email:** panwarmayank137@gmail.com
- **LinkedIn:** [linkedin.com/in/mynameismayank](https://linkedin.com/in/mynameismayank)


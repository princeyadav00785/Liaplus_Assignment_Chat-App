

# Real-Time Chat Application

This repository contains the source code for a real-time chat application built with **Node.js** for the backend, **React** (using Vite) for the frontend, and **WebSocket** technology for real-time communication.

## Features

- **Real-Time Messaging**: Powered by WebSocket for instant communication.
- **Backend**: Built with Node.js for a robust server-side implementation.
- **Frontend**: Created using React with Vite for a fast and modern development experience.
- **Seamless Integration**: Backend and frontend work together to deliver a smooth chat experience.
- **Room-based Chat**: Users enter a unique room name. If two users enter the same room name, they will join the same group chat.

---

## Repository Structure

```
Liaplus_Assignment_Chat-App/
├── client/    # Frontend code (React with Vite)
├── server/    # Backend code (Node.js with WebSocket)
```

---

## Prerequisites

Ensure you have the following installed on your system:

1. **Node.js** (v16 or higher recommended)
2. **npm** (Node Package Manager)
3. **Git** (to clone the repository)

---

## Setup Instructions

Follow these steps to set up and run the application:

### 1. Clone the Repository

```bash
git clone https://github.com/princeyadav00785/Liaplus_Assignment_Chat-App.git
cd Liaplus_Assignment_Chat-App
```

---

### 2. Start the Frontend (React with Vite)

```bash
cd client
npm install
npm run dev
```

The frontend will start and typically be accessible at `http://localhost:5173`.

### 3. Start the Backend (Node.js Server)

Open a new terminal, navigate to the server folder, and run the following:

```bash
cd server
node index.js
```

The server will start running and listening for WebSocket connections.

---

### 4. Access the Application

Once both the frontend and backend are running, open your browser and navigate to:

```
http://localhost:5173
```

On the homepage, users will be prompted to enter a **username** and a **room name**. If two or more users enter the same **room name**, they will automatically be connected in the same chat group, allowing them to communicate in real-time.

---
### App Screenshots : 

![Screenshot from 2025-01-12 16-12-52](https://github.com/user-attachments/assets/1ab09077-1a64-4c0c-8b25-b207f7ab980d)

![Screenshot from 2025-01-12 16-14-03](https://github.com/user-attachments/assets/fe91d6d9-a157-4c63-b4f3-1a446c782dd8)



## Contact

For any questions or issues, feel free to open an issue in the repository or reach out to the maintainer:

- **GitHub**: [princeyadav00785](https://github.com/princeyadav00785)

---
```


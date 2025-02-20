# Code Together

Code Together is a collaborative coding platform that allows multiple users to work on the same project in real-time. This user manual will guide you through the setup and usage of the platform.

## Table of Contents
- [Installation](#installation)
- [Running the Server](#running-the-server)
- [Connecting to the Server](#connecting-to-the-server)
- [Features](#features)
  - [User Management](#user-management)
  - [File Management](#file-management)
  - [Chat](#chat)
  - [Drawing](#drawing)
- [Troubleshooting](#troubleshooting)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/code-together.git
   cd code-together
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add the following:
   ```
   PORT=3000
   ```

## Running the Server

To start the server, run:
```bash
npm start
```
The server will start on the port specified in the `.env` file (default is 3000).

## Connecting to the Server

Open your browser and navigate to `http://localhost:3000`. You will see the Code Together interface.

## Features

### User Management

- **Join Room**: Users can join a room by providing a room ID and username.
- **User Status**: The platform shows the online/offline status of users.
- **Typing Indicator**: See when other users are typing.

### File Management

- **Sync File Structure**: The file structure is synchronized across all users in the room.
- **Create Directory**: Users can create new directories.
- **Update Directory**: Users can update existing directories.
- **Rename Directory**: Users can rename directories.
- **Delete Directory**: Users can delete directories.
- **Create File**: Users can create new files.
- **Update File**: Users can update the content of existing files.
- **Rename File**: Users can rename files.
- **Delete File**: Users can delete files.

### Chat

- **Send Message**: Users can send messages to the room.
- **Receive Message**: Users receive messages from other users in the room.

### Drawing

- **Request Drawing**: Users can request to start a drawing session.
- **Sync Drawing**: The drawing data is synchronized across all users.
- **Drawing Update**: Users can update the drawing and share snapshots.

## Troubleshooting

- **Server Not Starting**: Ensure that all dependencies are installed and the `.env` file is correctly configured.
- **Connection Issues**: Check if the server is running and accessible at the specified port.
- **Feature Not Working**: Check the browser console for any errors and ensure that the server logs do not show any issues.

For further assistance, please refer to the project's issue tracker on GitHub.

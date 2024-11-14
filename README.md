# Anon-Chat

Anon-Chat is a video chat application built with ReactJS, WebRTC, and Socket.IO. With the increased demand for remote communication, Anon-Chat allows users to easily connect over video calls. Inspired by popular platforms like Zoom and Skype, this project includes a unique twist and personal touch.

## Features

- Real-time Video Calls: Seamless video calls between users.
- Socket.IO for Communication: Manages real-time data exchange for connection establishment.
- WebRTC Integration: Uses WebRTC through Simple Peer to handle media streaming.
- Responsive Design: Adapts to different screen sizes for a better user experience.

## Tech Stack

- Frontend: ReactJS
- Backend: Node.js, Socket.IO
- WebRTC: Real-time media and data sharing

## Getting Started

### Prerequisities

- Node.js installed on your machine.

### Installation

1. Clone the repository:

    git clone https://github.com/yourusername/anon-chat.git

2. Navigate to the project directory:

    cd anon-chat

3. Install dependencies for both the client and server:

    npm install

## Running the Application

1. Start the server:

    npm run dev

2. Start the frontend

    cd frontend
    npm start

3. Open your browser and navigate to http://localhost:3000 to start a video call.

## How it Works

The application uses:

- Socket.IO to establish real-time communication.
- WebRTC (via Simple Peer) for peer-to-peer video streaming between users.
- React components to build a user-friendly and responsive interface.

## Future Improvements

- Screen sharing capabilities
- Improved UI/UX for better user interaction
- Add chat functionality during video calls


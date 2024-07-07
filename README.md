# Real-Time Video Chat Application

## Overview

This project aims to create a real-time video chat application using **WebRTC**, **Socket.io**, **React**, and **Node.js**. Users can join chat rooms, engage in video calls, and exchange messages seamlessly.

## Features

1. **User Authentication**:
   - Users can sign up or log in to access the application.
   - Authentication ensures secure access to video chat rooms.

2. **Video Chat Rooms**:
   - Users can create or join video chat rooms.
   - Each room has a unique URL for sharing with others.

3. **Real-Time Video and Audio Streaming**:
   - WebRTC enables low-latency video and audio communication.
   - Users can see and hear each other in real time.

4. **Chat Functionality**:
   - Alongside video calls, users can exchange text messages.
   - Chat messages appear in the same interface as video streams.

5. **Responsive UI**:
   - The application adapts to various devices (desktop, tablet, mobile).

## Tech Stack

- **Front-End**:
  - Built with **React**
  - Handles UI rendering, user authentication, and video chat controls

- **Back-End**:
  - Powered by **Node.js**
  - Manages WebSocket connections via **Socket.io**
  - Handles user authentication and room management
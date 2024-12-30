# Real-Time JSON Editor

This project consists of a **frontend** built in React.js and a **backend** built using FastAPI. It allows users to edit JSON data in real time, with the ability to render it as HTML on the client side. The application utilizes WebSockets for real-time updates and integrates an AI-powered dynamic editing feature using the Groq

## Project Overview

- **Frontend**: [Live Demo](https://jsonwebeditor.vercel.app/)
- **Backend**: [FastAPI Docs](http://ec2-13-49-68-118.eu-north-1.compute.amazonaws.com:8000/docs)

**Note**: The backend uses WebSockets (ws) instead of secure WebSockets (wss). Clone the repository to run it locally

## Tech Stack

This project utilizes the following technologies:

### Frontend
- **React.js**
- **Tailwind CSS**
- **ShadCN**

### Backend
- **FastAPI**:
- **PostgreSQL**: to store JSON data.
- **WebSockets**: used for real-time communication between the frontend and backend.

### AI Integration
- **Groq API**


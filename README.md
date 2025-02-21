# zocket_task_frontend-backend

# AI Task Manager

## Overview
AI Task Manager is a real-time task management system that leverages AI for smart task suggestions and automation. The system includes user authentication, task creation, assignment, tracking, and real-time updates through WebSockets.

## Features
- **User Authentication**: JWT-based authentication.
- **Task Management**: Create, assign, and track tasks.
- **AI-Powered Suggestions**: Smart task breakdowns using OpenAI/Gemini API.
- **Real-time Updates**: WebSockets for instant task updates.
- **Deployment**: Hosted on Render (Backend) and Vercel (Frontend).
- **Bonus**:
  - Docker & Kubernetes support.
  - Slack/Discord bot integration for notifications.
  - AI task automation based on priority.

## Tech Stack
### Backend
- **Golang (Gin Framework)**: REST API development.
- **PostgreSQL**: Database for storing tasks and users.
- **Goroutines & WebSockets**: Real-time updates.
- **JWT Authentication**: Secure login and session management.
- **Docker & Kubernetes**: Containerized deployment.
- **OpenAI/Gemini API**: AI-powered task recommendations.

### Frontend
- **Next.js (TypeScript)**: Modern React framework.
- **Tailwind CSS**: Utility-first styling.
- **JWT Authentication**: Secure client-side handling.
- **WebSockets**: Real-time task updates.
- **AI Chat**: Task recommendations powered by AI.

## Installation
### Prerequisites
- Go 1.19+
- Node.js 16+
- Docker (optional, for containerized deployment)
- PostgreSQL database

### Backend Setup
1. Navigate to the `backend/` directory:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   go mod tidy
   ```
3. Set up PostgreSQL and update `config/db.go` with your database credentials.
4. Start the backend server:
   ```sh
   go run main.go
   ```

### Frontend Setup
1. Navigate to the `frontend/` directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## Deployment
- **Backend**: Deploy using Render/Fly.io.
- **Frontend**: Deploy on Vercel.
- **Docker**:
  ```sh
  docker-compose up --build
  ```

## Usage
- Sign up and log in to manage tasks.
- Get AI-powered task suggestions.
- Receive real-time task updates.

## Contributing
Feel free to submit issues and pull requests.

## License
MIT License.


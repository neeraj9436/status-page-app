# Status Page Application

A modern status page application built with React (frontend) and FastAPI (backend) that allows users to monitor and display the status of various services.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Deployment](#deployment)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)

## Features
- Real-time status monitoring
- Clean and responsive UI built with React
- RESTful API built with FastAPI
- Status history tracking
- Incident reporting
- Customizable status checks
- Uptime tracking

## Project Structure
```
status-page-app/
├── frontend/          # React frontend application
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
│
└── backend/           # FastAPI backend application
    ├── app/
    ├── requirements.txt
    └── README.md
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Python (3.8 or higher)
- Git
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/status-page-app.git
cd status-page-app
```

2. Set up the frontend:
```bash
cd frontend
npm install
```

3. Set up the backend:
```bash
cd ../backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Configuration

### Frontend Configuration
1. Create a `.env` file in the frontend directory:
```env
REACT_APP_API_URL=http://localhost:8000
```


## Running the Application

### Start the Backend Server
```bash
cd backend
source venv/bin/activate  # On Windows: venv\Scripts\activate
uvicorn main:app --reload
```
The API will be available at `http://localhost:8000`

### Start the Frontend Development Server
```bash
cd frontend
npm start
```
The application will be available at `http://localhost:3000`




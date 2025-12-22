# AI Powered Interview Prep App

A full-stack web application that leverages AI to help users prepare for interviews. It features personalized question generation, session management, and user authentication, with a modern, responsive UI.

[![Interview Prep AI Homepage](frontend/public/homepage.png)](frontend/AI_Powered_Interview_Prep_App/public/homepage.png)
*Homepage of Interview Prep AI*

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Folder Structure](#folder-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

---

## Features
- AI-powered interview question generation
- User authentication (sign up, login)
- Session management and history
- Profile photo upload
- Responsive dashboard and UI
- Real-time feedback and summaries

## Tech Stack
- **Frontend:** React, Vite, CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **AI Integration:** Gemini API

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### Clone the repository
```sh
git clone https://github.com/bled1908/AI_Powered_Interview_Prep_App.git
cd AI_Powered_Interview_Prep_App
```

---

## Backend Setup
```sh
cd backend
npm install
# Configure your database in config/db.js
npm run dev
```

## Frontend Setup
```sh
cd frontend/AI_Powered_Interview_Prep_App
npm install
npm run dev
```

---

## Folder Structure
```
backend/
  controllers/      # Route handlers
  middlewares/      # Express middlewares
  models/           # Mongoose models
  routes/           # API routes
  utils/            # Utility functions
frontend/AI_Powered_Interview_Prep_App/
  src/
    components/     # Reusable UI components
    pages/          # Page components
    context/        # React context
    utils/          # Helper functions
```

---

## API Endpoints
- `POST /api/auth/login` — User login
- `POST /api/auth/signup` — User registration
- `GET /api/questions` — Get AI-generated questions
- `POST /api/sessions` — Create a new session
- `GET /api/sessions/:id` — Get session details

---

## Contributing
1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## License
This project is licensed under the MIT License.

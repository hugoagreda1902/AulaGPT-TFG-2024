  # AulaGPT — AI Assistant for Education

An AI-powered assistant designed to support students and teachers by improving access to educational content, document management and interaction through natural language.

AulaGPT combines a backend API with a web-based frontend to provide an interactive assistant focused on learning environments.

---

## Overview

AulaGPT is a full-stack application built as a final degree project (TFG) that explores how artificial intelligence can be integrated into educational workflows.

The system allows users to interact with an AI assistant, manage authentication, and connect with external services such as Google Drive to support document-based learning scenarios.

The project focuses on clean separation between backend and frontend, API-driven communication and practical use of AI technologies.

---

## What It Does

- Provides an AI-powered chat interface for students and teachers  
- Handles user authentication and authorization  
- Integrates external services (e.g. Google Drive) for document access  
- Exposes a REST API for frontend communication  
- Manages structured data through a backend framework  
- Separates concerns between backend logic and frontend UI  

---

## Architecture

The project is divided into two main components:

- **Backend**: REST API built with Python (Django)
- **Frontend**: Web application built with React

Communication between both layers is handled through HTTP APIs.

Frontend (React)
↓
REST API (Django)
↓
Database / External Services

---

## Key Technologies

- **Python** — Backend development
- **Django** — REST API and application logic
- **JavaScript** — Frontend logic
- **React** — User interface
- **Axios** — API communication
- **Google Drive API** — External document integration
- **SQLite / relational DB** — Data persistence
- **Git** — Version control

---

## Project Structure

Aula-GPT/
├── aula-gpt-backend/
│ ├── api/
│ │ ├── google_drive/
│ │ │ ├── credentials.json
│ │ │ └── utils.py
│ │ ├── migrations/
│ │ ├── admin.py
│ │ ├── models.py
│ │ ├── serializers.py
│ │ ├── urls.py
│ │ └── views.py
│ ├── aula_backend/
│ │ ├── settings.py
│ │ ├── urls.py
│ │ ├── asgi.py
│ │ └── wsgi.py
│ ├── manage.py
│ ├── requirements.txt
│ └── .gitignore
│
├── aula-gpt-frontend/
│ ├── public/
│ │ └── index.html
│ ├── src/
│ │ ├── api/
│ │ │ ├── axiosConfig.js
│ │ │ └── dataService.js
│ │ ├── components/
│ │ │ ├── ChatIA.jsx
│ │ │ ├── Home.jsx
│ │ │ ├── Login.jsx
│ │ │ └── Register.jsx
│ │ ├── context/
│ │ │ └── AuthContext.js
│ │ ├── styles/
│ │ ├── utils/
│ │ ├── App.js
│ │ └── index.js
│ ├── package.json
│ └── README.md
│
├── package.json
├── requirements.txt
└── README.md

---

### Backend

cd aula-gpt-backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

### Frontend

cd aula-gpt-frontend
npm install
npm start

---

### Use Cases

Educational AI assistant for students
Support tool for teachers
Experimentation with AI-assisted learning workflows
Full-stack academic project with real-world architecture

---

### Project Status

Academic project (Final Degree Project – TFG)
Functional prototype
Open to future improvements and extensions

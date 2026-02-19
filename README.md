# AulaGPT — AI Assistant for Education

AulaGPT is a full-stack application built as a final degree project (TFG) that explores how artificial intelligence can be integrated into educational workflows.

The system allows users to interact with an AI assistant, manage authentication, and connect with external services such as Google Drive to support document-based learning scenarios.

The project focuses on clean separation between backend and frontend, API-driven communication and practical use of AI technologies.

---

## Link to view

https://aulagpt.netlify.app/
---

## Project score 

7/10

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

### Backend

- cd aula-gpt-backend
- python -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- python manage.py migrate
- python manage.py runserver

### Frontend

- cd aula-gpt-frontend
- npm install
- npm start

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




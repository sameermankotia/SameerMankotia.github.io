# AI Academic Advisor

## Overview
The **AI Academic Advisor** is a full-stack web application developed using **React and Flask**. It provides intelligent academic planning assistance for Computer Science students through AI-powered course recommendations and interactive degree planning. The application uses **Llama 3.2 AI model** integrated with **Ollama** for personalized academic guidance and **SQLite/PostgreSQL** as the backend database.

---

## Features
- **AI-Powered Recommendations**: Get personalized course suggestions based on academic progress and career goals.
- **Interactive Course Planning**: Drag-and-drop interface for planning 4-year degree schedule across 8 academic terms.
- **Prerequisite Validation**: Automatic checking of course dependencies and graduation requirements.
- **Academic Progress Tracking**: Real-time degree completion percentage and credit load management.
- **Course Catalog**: Browse 30+ Computer Science courses with difficulty ratings and detailed information.
- **Plan Management**: Save, export, import, and share academic plans with validation feedback.

---

## Technology Stack
### Frontend:
- **React 19.1.0**: Modern JavaScript library for building user interfaces.
- **TailwindCSS**: Utility-first CSS framework for responsive design.
- **@hello-pangea/dnd**: Professional drag-and-drop functionality.

### Backend:
- **Flask 2.3.3**: Lightweight Python web framework.
- **SQLAlchemy**: Object-relational mapping (ORM) for database operations.
- **Flask-CORS**: Cross-origin resource sharing support.
- **Flask-JWT-Extended**: Authentication and authorization.

### AI/ML:
- **Ollama**: Local AI model hosting and management platform.
- **Llama 3.2**: Meta's advanced language model for academic recommendations.
- **Custom Model Training**: Fine-tuned model specifically for CS curriculum guidance.

### Database:
- **SQLite**: Lightweight database for development.
- **PostgreSQL**: Scalable relational database for production.

### Development Tools:
- **Vite**: Fast build tool and development server for React.
- **Python Virtual Environment**: Isolated Python package management.
- **Node.js & npm**: JavaScript runtime and package manager.
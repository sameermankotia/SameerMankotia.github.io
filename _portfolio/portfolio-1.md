# Smart Advisor - AI-Powered Academic Planning System

> **An intelligent academic planning platform that revolutionizes how Computer Science students navigate their 4-year degree journey through AI-powered recommendations and intuitive drag-and-drop scheduling.**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black.svg)](https://github.com/sameermankotia/AI-Advisor/tree/master)
[![React](https://img.shields.io/badge/React-19.1.0-61dafb.svg)](https://reactjs.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3.3-000000.svg)](https://flask.palletsprojects.com/)
[![AI](https://img.shields.io/badge/AI-Llama%203.2-ff6b35.svg)](https://ollama.ai/)

---

## 🎯 Project Overview

Smart Advisor addresses the critical challenge of academic planning for Computer Science students at the University of Idaho. By combining artificial intelligence with an intuitive user interface, the platform provides personalized course recommendations, validates academic plans, and optimizes graduation timelines.

**Key Achievement**: Developed a comprehensive full-stack solution that integrates local AI models with modern web technologies to deliver real-time academic guidance.

---

## 🚀 Key Features & Innovations

### **AI-Driven Academic Intelligence**
- **Custom Llama 3.2 Integration**: Deployed and fine-tuned local AI model specifically for CS curriculum guidance
- **Intelligent Course Sequencing**: Automated prerequisite tracking with optimization algorithms
- **Personalized Recommendations**: Context-aware suggestions based on student performance and career goals
- **Real-time Plan Validation**: Instant feedback on course selections with graduation timeline analysis

### **Advanced User Experience**
- **Professional Drag & Drop Interface**: Seamless course placement across 8 academic terms
- **Real-time Data Visualization**: Dynamic progress tracking with credit load indicators
- **Comprehensive Validation System**: Automatic prerequisite checking and credit limit enforcement
- **Export/Import Functionality**: Plan persistence and sharing capabilities

### **Enterprise-Grade Architecture**
- **RESTful API Design**: Scalable backend with comprehensive endpoint coverage
- **Robust Database Schema**: Normalized data structure supporting complex academic relationships
- **Modern Frontend Architecture**: Component-based React application with state management
- **AI Service Integration**: Seamless communication with local AI model hosting

---

## 🛠️ Technical Implementation

### **Frontend Architecture**
```
React 19.1.0 + TypeScript
├── Component-based architecture with hooks
├── @hello-pangea/dnd for drag-and-drop functionality
├── TailwindCSS for responsive design system
├── Context API for state management
└── Vite for optimized builds and development
```

### **Backend Infrastructure**
```
Flask 2.3.3 + Python
├── SQLAlchemy ORM with relationship modeling
├── JWT-based authentication system
├── CORS-enabled API endpoints
├── Comprehensive error handling
└── Database migration management
```

### **AI/ML Integration**
```
Ollama + Llama 3.2
├── Local AI model deployment
├── Custom model fine-tuning for academic domain
├── Real-time inference capabilities
├── Context-aware response generation
└── Academic data training pipeline
```

### **Database Design**
```sql
Normalized Schema Design:
├── Students (user profiles, academic standing)
├── Courses (curriculum data, prerequisites)
├── Terms (academic scheduling, deadlines)
├── Enrollments (student-course relationships)
└── AcademicPlans (degree planning, progress tracking)
```

---

## 💡 Problem Solving & Innovation

### **Challenge**: Complex Academic Planning
**Solution**: Developed an AI-powered system that understands intricate prerequisite chains and provides intelligent course sequencing recommendations.

### **Challenge**: User Experience Complexity  
**Solution**: Implemented intuitive drag-and-drop interface with real-time validation, making complex academic planning accessible to all users.

### **Challenge**: Scalable AI Integration
**Solution**: Architected local AI model deployment with Ollama, ensuring data privacy while maintaining real-time performance.

### **Challenge**: Data Integrity & Validation
**Solution**: Built comprehensive validation system preventing academic planning errors through automated prerequisite checking and credit limit enforcement.

---

## 📊 Technical Achievements

- **Full-Stack Development**: End-to-end application development from database design to user interface
- **AI Model Integration**: Successfully deployed and customized Llama 3.2 for domain-specific applications
- **Modern Web Technologies**: Implemented latest React patterns and Flask best practices
- **Database Optimization**: Designed efficient schema supporting complex academic relationships
- **API Architecture**: Created RESTful endpoints with comprehensive error handling and documentation
- **Responsive Design**: Built mobile-first interface with professional UI/UX standards

---

## 🎨 User Interface Highlights

### **Interactive Course Planning**
- Smooth drag-and-drop functionality with visual feedback
- Real-time credit calculation and semester load indicators
- Professional animations and micro-interactions
- Responsive design adapting to all screen sizes

### **AI Advisor Interface**
- Natural language processing for academic queries
- Context-aware responses with specific course recommendations
- Real-time chat interface with typing indicators
- Integration with student academic data for personalized advice

### **Academic Dashboard**
- Progress visualization with degree completion tracking
- GPA integration and academic standing indicators
- Course difficulty ratings and workload balancing
- Export functionality for academic planning documents

---

## 🔧 Development & Deployment

### **Local Development Setup**
```bash
# Backend Environment
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python run.py

# Frontend Environment  
npm install && npm run dev

# AI Model Setup
ollama pull llama3.2
ollama create enhanced-academic-advisor -f Modelfile
```

### **Production Deployment**
- **Frontend**: Vercel deployment with automatic builds
- **Backend**: Railway hosting with PostgreSQL database
- **AI Service**: Self-hosted Ollama instance with model persistence
- **Monitoring**: Comprehensive logging and error tracking

---

## 📈 Impact & Results

- **User Experience**: Streamlined academic planning process from hours to minutes
- **Data Accuracy**: Eliminated common prerequisite errors through automated validation
- **AI Integration**: Successfully demonstrated local AI model deployment for educational applications
- **Scalable Architecture**: Built foundation supporting hundreds of concurrent users
- **Modern Technology Stack**: Showcased proficiency in cutting-edge web development technologies

---

## 🚀 Future Enhancements

- **Advanced Analytics**: Student success prediction models
- **Multi-University Support**: Expandable curriculum database
- **Mobile Application**: Native iOS/Android development
- **Integration APIs**: Campus system connectivity
- **Advanced AI Features**: Natural language course search and recommendation engines

---

## 🛠️ Technologies Demonstrated

**Frontend**: React 19, TypeScript, TailwindCSS, Vite, Component Architecture  
**Backend**: Python, Flask, SQLAlchemy, RESTful APIs, JWT Authentication  
**Database**: SQLite/PostgreSQL, Schema Design, Data Modeling  
**AI/ML**: Ollama, Llama 3.2, Model Fine-tuning, Local Deployment  
**DevOps**: Git, Docker, Cloud Deployment, Environment Management  
**Tools**: Modern Development Workflow, Testing, Documentation

---

## 📞 Project Links

- **[Live Demonstration](your-demo-url)** - Interactive project showcase
- **[GitHub Repository](your-github-url)** - Complete source code and documentation
- **[Technical Documentation](your-docs-url)** - Detailed implementation guide
- **[API Documentation](your-api-docs-url)** - Comprehensive endpoint reference

---

*This project demonstrates comprehensive full-stack development skills, AI integration capabilities, and modern web application architecture. Built as part of academic portfolio showcasing practical software engineering expertise.*
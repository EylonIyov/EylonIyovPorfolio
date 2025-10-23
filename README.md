# 🚀 My Software Development Portfolio

Welcome to my portfolio showcasing two full-stack applications that demonstrate my expertise in modern web and mobile development technologies.

---

## 📁 Projects Overview

### 1. 🤖 Computer Use Agent
**Repository:** [github.com/EylonIyov/LLM-With-Eyes](https://github.com/EylonIyov/LLM-With-Eyes)

An AI-driven computer-use agent that observes the screen, detects UI elements, reasons over them, and acts via mouse/keyboard tools.  
Implements grounded actions, strict JSON communication with VLMs, and screenshot-based feedback loops — enabling automation that “sees” and interacts with real interfaces.

**Highlights:**
- 🖼️ Vision-Language reasoning over detected UI boxes with OCR text.
- 🧠 JSON-based decision schema for deterministic, interpretable actions.
- ⚙️ Built on **Python**, **OpenAI SDK**, **PyAutoGUI**, **LM Studio**, and **custom OCR/CV modules**.
- 🪟 Fully local execution pipeline for Windows using MCP tools.

- ### 2. 🐕 DogApp - Pet Management and Social Platform
**Repository:** [github.com/EylonIyov/dogappv2](https://github.com/EylonIyov/dogappv2)

A comprehensive full-stack mobile and web application designed for pet owners to manage their furry friends' profiles and activities.
 
### 3. 📈 Stocks Portfolio Management System
**Repository:** [github.com/EylonIyov/Stocks-App](https://github.com/EylonIyov/Stocks-App)

A microservices-based stock portfolio management system with real-time tracking, capital gains calculation, and horizontal scaling capabilities.

---

## 🛠️ Tech Stack Comparison

### DogApp  - Mobile-First Architecture

#### Frontend
- **React Native** with **Expo** - Cross-platform mobile development
- **React Navigation** - Seamless screen transitions
- **Context API** - State management
- **Responsive Design** - iOS, Android, and Web support

#### Backend
- **Node.js** - Server runtime
- **Express.js** - RESTful API framework
- **Firebase** - Authentication & Real-time database
- **Cloud Storage** - Pet photo management

#### Key Features
- 🔐 User authentication (signup/login)
- 📝 CRUD operations for dog profiles
- 📸 Photo upload and storage
- 📱 Cross-platform compatibility
- 🔄 Real-time data synchronization

---

### Stocks App - Microservices Architecture

#### Infrastructure
- **Docker & Docker Compose** - Container orchestration
- **Nginx** - Load balancer & reverse proxy
- **MongoDB** - NoSQL database with volume persistence

#### Backend Services
- **Flask (Python)** - Microservices framework
- **Multiple Service Instances** - Horizontal scaling
- **Alpha Vantage API** - Real-time stock data
- **RESTful API** - Clean endpoint design

#### Architecture Highlights
```
┌──────────────┐
│   Nginx 80   │ (Load Balancer)
└───┬─────┬────┘
    │     │
┌───▼───┐ ┌───▼───┐
│Stock1 │ │Stock2 │ (Multiple Instances)
└───┬───┘ └───┬───┘
    │         │
┌───▼─────────▼───┐
│  Capital Gains  │ (Aggregation Service)
└────────┬────────┘
         │
┌────────▼────────┐
│    MongoDB      │ (Persistent Storage)
└─────────────────┘
```

---

## 💡 Technical Expertise Demonstrated

### Mobile & Web Development
- **Cross-platform Development**: Building once, deploying everywhere with React Native/Expo
- **Responsive Design**: Ensuring seamless UX across all devices
- **User Authentication**: Implementing secure login systems with Firebase

### Backend Development
- **API Design**: RESTful principles with clear endpoint structure
- **Microservices**: Distributed architecture with service isolation
- **Database Management**: Both NoSQL (MongoDB) and Firebase implementations

### DevOps & Infrastructure
- **Containerization**: Docker-based deployment strategies
- **Load Balancing**: Nginx configuration for traffic distribution
- **Horizontal Scaling**: Multiple service instances with weighted routing
- **Environment Management**: Proper configuration through environment variables

### Best Practices
- **Clean Code Architecture**: Separation of concerns across services
- **Version Control**: Git-based workflow with clear documentation
- **Error Handling**: Graceful failure recovery (auto-restart mechanisms)
- **Security**: Authentication, secure data storage, and API protection

---

## 🎯 Project Goals & Learning Outcomes

### DogApp v2
- **Goal**: Create a user-friendly platform for pet management
- **Challenge**: Integrating real-time features with offline capabilities
- **Solution**: Firebase for sync and local caching strategies

### Stocks App
- **Goal**: Build a scalable financial tracking system
- **Challenge**: Handling concurrent requests and ensuring data consistency
- **Solution**: Microservices architecture with load balancing

---

## 📊 Technical Skills Summary

| Category | Technologies |
|----------|-------------|
| **Languages** | JavaScript, Python, HTML/CSS |
| **Frontend** | React Native, Expo, React Navigation |
| **Backend** | Node.js, Express, Flask |
| **Databases** | MongoDB, Firebase |
| **DevOps** | Docker, Docker Compose, Nginx |
| **Cloud Services** | Firebase Auth, Cloud Storage |
| **APIs** | RESTful design, Alpha Vantage integration |
| **Version Control** | Git, GitHub |

---

## 🚀 Future Enhancements

### DogApp v2
- 📍 Geolocation features for dog park check-ins
- 👥 Social networking for pet owners
- 📅 Appointment scheduling and reminders
- 💬 In-app messaging system

### Stocks App
- 📈 WebSocket integration for live price updates
- 🤖 CI/CD pipeline with GitHub Actions

---

## 📫 Contact

**Developer**: Eylon Iyov  
**Institution**: Reichman University, 2025

Feel free to explore the repositories and reach out if you have any questions about the implementation details or technical decisions!

---

*Built with ❤️ and a passion for clean, scalable code*

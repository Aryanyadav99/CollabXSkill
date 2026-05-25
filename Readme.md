#  CollabXSkill

![React](https://img.shields.io/badge/Frontend-React-blue)
![Vite](https://img.shields.io/badge/Build-Vite-purple)
![Spring Boot](https://img.shields.io/badge/Backend-SpringBoot-green)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Redis](https://img.shields.io/badge/Cache-Redis-red)

CollabXSkill is a full-stack developer collaboration platform that helps developers find the right tech partners based on skills, experience, and intent — not random connections.

Built with a production-grade backend architecture, secure authentication, and real-time communication.

---

# 🌐 Live Deployment

## Frontend (React + Vite)
https://collabxskill.me

## Backend API
https://collabxiq.onrender.com

> ⚠️ Backend is deployed on Render free tier, so the server may take a few seconds to wake up initially.

---

# 📦 Repositories

## Frontend Repository (AI Help)
https://github.com/Aryanyadav99/CollabXSkill-Frontend

## Backend Repository (BY ME completely)
https://github.com/Aryanyadav99/CollabXIQ 

---

# 🛠 Tech Stack

## Frontend
- React
- Vite
- Tailwind CSS

## Backend
- Java
- Spring Boot
- PostgreSQL
- Redis
- JWT Authentication
- Refresh Token Rotation
- WebSocket + STOMP
- Docker

---

# ⚡ Problem

Developers often struggle to:

- Find the right collaborators for projects
- Get help in specific tech stacks
- Avoid noisy and unstructured platforms

Most existing platforms are:

- Too formal
- One-sided
- Random and unfiltered

---

# 💡 Solution

CollabXSkill introduces a skill-based matching engine combined with a mutual interaction system, enabling developers to:

- Discover relevant collaborators
- Express intent clearly
- Start meaningful conversations only when both sides are interested

---

# ✨ Key Features

## ⚡ Weighted Matching Algorithm

Each developer profile is ranked using:

- Same domain → +40 pts
- Common tech stack → +10 per match
- Same experience → +20 pts

Ensures highly relevant matches and eliminates random discovery.

---

## 🔥 SUPER COLLAB (Priority Requests)

Send high-priority collaboration requests.

Example:

> “48hr hackathon — need a Spring Boot dev”

- Limited to 3/day
- Always appears at the top

---

## 🤝 Silent Matching System

- Mutual interest unlocks chat automatically
- No cold DMs or spam

---

## 🔒 Granular Interaction Controls

- Temporary rejection (7 days)
- Permanent block system

Human-first interaction design.

---

## 💬 Real-Time Chat System

- WebSocket + STOMP integration
- Secure real-time messaging between matched users

---

## 🛡️ Security & Authentication

- JWT Authentication
- Refresh Token Rotation
- Token Versioning
- Secure WebSocket handshake using JWT
- Rate limiting on sensitive endpoints

---

# ⚙️ Backend Engineering Highlights

- Clean layered architecture
- DTO-based request/response handling
- Global exception handling
- Centralized constants & enums
- Pagination for scalable APIs
- Data initialization for testing

---

# 📡 API Documentation

Swagger / OpenAPI integration support for:

- Endpoint testing
- Request/response validation
- Authentication flow testing

---

# 📁 Project Structure

```bash
collabxskill/
├── frontend/        # React + Vite frontend
├── backend/         # Spring Boot backend
```

---

# 🚀 Getting Started

## Prerequisites

- Java 17+
- Maven
- PostgreSQL
- Node.js
- npm

---

## Clone Repository

```bash
git clone https://github.com/Aryanyadav99/CollabXSkill.git
```

---

## Backend Setup

```bash
cd backend
./mvnw spring-boot:run
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# 📸 Screenshots

_Add screenshots here later_

---

# 🧾 Commit Style

Following clean and structured commit conventions:

- `feat:` → new features
- `fix:` → bug fixes
- `refactor:` → code improvements

---

# 🚧 Future Enhancements

- Cloudinary integration
- AWS deployment
- AI-based collaborator recommendations
- Premium collaboration tools
- Notification system

---

# 🎯 Vision

To build a platform where developers don’t just connect —
they find, match, and build together efficiently.

---

# 🤝 Contribution

Contributions are welcome.

Please maintain:

- Clean commit messages
- Proper API documentation
- Code consistency

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

---

# 👨‍💻 Author

Aryan

<div align="center">

# 🚀 Discode.dev

### Modern real-time messaging for teams
**Secure communication -  Integrated AI -  Scalable architecture**

[![Website](https://img.shields.io/badge/Website-discode.dev-blue?style=for-the-badge)](https://discode.dev)
[![Status](https://img.shields.io/badge/Status-Beta-yellow?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-Closed_Source-red?style=for-the-badge)]()

[🌐 discode.dev](https://discode.dev) • [📖 Documentation](#documentation) • [✨ Features](#features) • [🛠️ Stack](#tech-stack)

</div>

***

## 📖 About

**Discode** is a modern instant messaging platform designed for teams that want to communicate effectively. Developed as a student project, Discode combines best practices of modern web development with innovative AI-powered features.

> ⚠️ **Note**: This repository is a showcase. The source code is private but available on request for academic or professional evaluation.

### 🎯 Project goals

- Learn modern web architectures (microservices, real-time)
- Experiment with AI integration in a real application
- Create an educational alternative to commercial solutions
- Practice development and security best practices

***

## ✨ Features

### 🔥 Key features

- **💬 Real-time Messaging**
  - Instant messages via WebSocket (Socket.IO)
  - Presence and typing indicators
  - Persistent conversation history
  - Support for reactions and emojis

- **🤖 Artificial Intelligence**
  - Automatic content moderation
  - Contextual reply suggestions
  - Conversation summaries
  - Spam and inappropriate content detection

- **🔒 Security & Authentication**
  - JWT for authentication
  - Password hashing (bcrypt)
  - CSRF and XSS protection
  - Server-side validation

- **👥 Team Management**
  - Servers and channels
  - Roles and permissions
  - Link-based invitations
  - Advanced administration

- **🎨 Modern Interface**
  - Responsive design (mobile-first)
  - Dark theme by default
  - Smooth animations
  - Reusable components

***

## 🛠️ Tech Stack

### Frontend
```
⚛️  React 18 + TypeScript
🎨  CSS Modules + CSS Grid/Flexbox
🔄  React Router v6
🌐  Socket.IO Client
📦  Vite (Build Tool)
```

### Backend
```
🟢  Node.js + Express
🔌  Socket.IO (WebSocket)
🗄️  PostgreSQL (Database)
🔴  Redis (Cache & Sessions)
🔐  JWT + bcrypt (Security)
🤖  OpenAI API (AI)
```

### DevOps & Tools
```
🐳  Docker + Docker Compose
🚀  Prisma ORM
📝  ESLint + Prettier
🧪  Jest (Tests - coming soon)
📊  GitHub Actions (CI/CD - planned)
```

***

## 🏗️ Architecture

### Overview

IMG
### Data flow

1. **Authentication**: JWT stored in localStorage, validated on each request
2. **Messaging**: Bidirectional WebSocket via Socket.IO
3. **Persistence**: PostgreSQL with Prisma ORM
4. **Cache**: Redis for sessions and frequently accessed data
5. **AI**: OpenAI API calls for moderation and suggestions

> 📄 [Detailed architecture documentation](docs/architecture.md)

***

## 📸 Screenshots

<div align="center">

### Main Interface
![Chat Interface](assets/screenshots/chat-interface Management
![Servers](assets/screenshots/servers Moderation
![AI Moderation](assets/screenshots/ai-features Roadmap

### ✅ Phase 1 - MVP (Q4 2024)
- [x] User authentication
- [x] Real-time messaging
- [x] Server/channel creation
- [x] Basic interface

### 🚧 Phase 2 - Current (Q1 2025)
- [x] AI integration (moderation)
- [x] UX/UI improvements
- [ ] Advanced permissions system
- [ ] Performance optimization

### 📋 Phase 3 - Next (Q2 2025)
- [ ] Voice calls (WebRTC)
- [ ] File sharing
- [ ] Push notifications
- [ ] Automated tests

### 🔮 Phase 4 - Future (2025+)
- [ ] Mobile app (React Native)
- [ ] Bots and webhooks
- [ ] Public API
- [ ] Simplified self-hosting

***

## 📊 Statistics

- **Lines of code**: ~15,000+
- **Development duration**: 6 months
- **Technologies**: 12+ frameworks/libraries
- **Commits**: 300+
- **Uptime**: ~99% (test environment)

***

## 🎓 Academic Context

This project was developed as part of [Name of the school/program]. The learning objectives were:

- Master a complete modern web stack
- Understand real-time architectures
- Integrate third-party AI services
- Apply web security principles
- Manage a project end to end (design → deployment)

**Supervisor**: [Professor’s name if applicable]  
**Duration**: [Dates]  
**Team**: [Solo / Names if a team]

***

## 🤝 Contribution & Feedback

Although the source code is private, open to:

- 💡 **Feature suggestions**
- 🐛 **Bug reports** (via the production app)
- 💬 **UX/UI feedback**
- 🤔 **Technical questions**

### How to contribute?

1. Test the app at [discode.dev](https://discode.dev)
2. Open an [Issue](../../issues) for feedback/bugs
3. Join the [Discussion](../../discussions) for suggestions

***

## 📧 Contact

**Developer**: HamoudE  
**Email**: [ton-email@example.com]  
**LinkedIn**: [Ton profil]  
**Portfolio**: [ton-site.com]

***

## 📜 License & Usage

This project is **closed-source** and for **non-commercial educational** use.

- ✅ Free personal use
- ✅ Academic/portfolio demonstration
- ❌ Code distribution without authorization
- ❌ Commercial use

The source code can be shared upon request for:
- Academic evaluation
- Technical interviews
- Potential collaborations

***

## 🙏 Acknowledgments

- OpenAI for the GPT API
- Discord & Telegram for design inspiration
- Stack Overflow for... everything
- My coffee machine for the moral support

***

<div align="center">

**Made with ❤️ and lots of ☕**

[⭐ Star this repo if you find the project interesting!](../../stargazers)

</div>    

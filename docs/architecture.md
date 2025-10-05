# Discode

Real-time web messaging app with Node.js, WebSocket, React, and AI.

> **Note**: This is a showcase repository for portfolio purposes. The source code is proprietary and not available for public use.

A modern messaging application inspired by Discord, Telegram, or Messenger, developed **from A to Z**, with a smooth interface, **real-time communication**, and enriched with **AI features**.  
The project is designed to be **100% web-based**, **secure**, **scalable**, and above all, **fully controlled down to the smallest detail**.

---

## 📂 Project Overview

```
Discode/
├── client/                   // Frontend (React + Vite)
│   ├── src/
│   │   ├── components/       // Reusable UI components (Messages Friends, Profile...)
│   │   ├── hooks/            // Custom React hooks (Auth, Socket, Messages...)
│   │   ├── pages/            // Application pages (Auth, Home, MainLayout)
│   │   ├── lib/              // Client services (API, WebSocket, caching)
│   │   ├── styles/           // Component-scoped CSS modules
│   │   └── types/            // TypeScript definitions
│   └── vite.config.ts
│
├── server/                   // Backend (Node.js + Express + Socket.IO)
│   ├── prisma/               // Database schema & migrations
│   ├── src/
│   │   ├── controllers/      // Request handlers (auth, messages, users...)
│   │   ├── services/         // Business logic layer
│   │   ├── routes/           // API endpoints definition
│   │   ├── middlewares/      // Auth, validation, error handling
│   │   ├── sockets/          // Real-time WebSocket events
│   │   └── utils/            // Shared utilities (JWT, hashing, encryption)
│   └── uploads/              // User-uploaded files
│
├── shared/                   // Shared TypeScript types (front/back)
└── Mockup/                   // Design mockups & architecture docs
```

---

## 📦 Tech Stack

### Frontend
| Component       | Technology           | Role                                 |
|-----------------|----------------------|--------------------------------------|
| Framework       | **React 18**         | Modern UI with custom hooks          |
| Language        | **TypeScript**       | Static typing                        |
| Build Tool      | **Vite**             | Fast bundler and dev server          |
| Styling         | **CSS Modules**      | Component-scoped styles              |
| Real-time       | **Socket.IO Client** | WebSocket instant messaging          |

### Backend
| Component       | Technology           | Role                                 |
|-----------------|----------------------|--------------------------------------|
| Runtime         | **Node.js**          | JavaScript server runtime            |
| Framework       | **Express.js**       | REST API + server logic              |
| Language        | **TypeScript**       | Static typing                        |
| Real-time       | **Socket.IO**        | WebSocket server                     |
| Database        | **PostgreSQL**       | Relational database                  |
| ORM             | **Prisma**           | Type-safe database access            |
| Authentication  | **JWT** + **bcrypt** | Secure tokens and password hashing   |

### Planned Technologies
- **Redis** - Sessions, queues, ephemeral messages
- **OpenAI API** - Moderation, suggestions, summaries
- **Docker** - Containerization
- **VPS Hosting** - Self-hosted deployment

---

## 🏗️ Architecture Highlights

### Frontend Architecture

**Custom Hooks:**
- Authentication guard for protected routes
- WebSocket connection lifecycle management
- Message state and real-time updates
- Direct message contacts management
- User profile data synchronization

**Component Structure:**
- Clean separation between pages and reusable components
- Service layer for API and WebSocket communication
- Type-safe data flow with TypeScript

### Backend Architecture

**MVC Pattern:**
- Controllers for HTTP request handling
- Services for business logic and database operations
- Middleware pipeline for auth, validation, and error handling
- Real-time event system with Socket.IO

**API Structure:**
- RESTful endpoints for CRUD operations
- JWT-based authentication with refresh tokens
- WebSocket events for instant messaging
- File upload handling with optimization

---

## ✨ Key Features

### Authentication & Security
- Secure JWT-based authentication
- Password hashing with bcrypt
- Protected API endpoints
- Token refresh mechanism
- Input validation and sanitization

### Real-time Messaging
- Instant message delivery via WebSocket
- Message history with pagination
- Typing indicators
- Online/offline user status
- Read receipts

### User Experience
- Responsive design with smooth animations
- Dark mode support
- Customizable user profiles
- Avatar upload with WebP optimization
- Friend system with contact management

---

## 🛣️ Development Roadmap

### ✅ Completed
- [x] JWT authentication system
- [x] Real-time WebSocket communication
- [x] PostgreSQL database with Prisma ORM
- [x] Responsive React interface
- [x] Direct messaging functionality
- [x] User profiles and avatars
- [x] Friend management system

### 🚧 In Progress
- [ ] Group chat functionality
- [ ] Request rate limiting
- [ ] Redis caching layer
- [ ] AI-powered content moderation

### 🔮 Planned
- [ ] Voice and video calls
- [ ] End-to-end encryption
- [ ] File sharing
- [ ] Message reactions
- [ ] Multi-language support
- [ ] PWA (Progressive Web App)
- [ ] Public API for integrations

---

## 🔎 Project Philosophy

* **Understand before using**: No plug-and-play solutions, priority to technical understanding
* **Quality > quantity**: Every feature must be useful and well-integrated
* **Scalable**: Code must be easily evolvable in the future
* **Handcrafted but professional**: Build everything yourself, done right

---

## 📸 Screenshots

*Coming soon - Interface mockups and live demo screenshots*

---

## 📝 License

**Copyright © 2025 - All Rights Reserved**

This project and its source code are **proprietary and confidential**. Unauthorized copying, distribution, modification, or use of this software, via any medium, is strictly prohibited without explicit written permission from the owner .

This repository is maintained as a **portfolio showcase** to demonstrate technical capabilities and project architecture.

---

## 📧 Contact

For inquiries about this project, please reach out via:
- Email: contacts@discode.dev
- GitHub: [@HamooudE]

---

*Built with attention to detail. This project represents days of learning, iteration, and prompts.*

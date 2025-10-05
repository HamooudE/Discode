# Discode

## Modern Messaging (Almost) Like the Pros

Real-time chat built from scratch by a student. Ambitious architecture, handcrafted code, and beginner bugs included. Open source because we learn in public.

[View code](#) • [Try the demo](#)

---

## 🎯 Tech Stack (Not Copy-Pasted)

| Tech | Why | Status |
|------|-----|--------|
| ⚛️ **React 18** | Custom hooks everywhere | ✅ Mastered |
| 🟢 **Node.js + Express** | REST API + WebSocket server | ✅ Solid |
| ⚡ **Socket.IO** | Real-time messaging | ✅ Stable |
| 🛢️ **PostgreSQL** | Relational database | ✅ Operational |
| 🌐 **Prisma ORM** | Type-safe DB queries | ✅ In production |
| 🔐 **JWT + bcrypt** | Secure auth | ✅ Functional |
| 🔴 **Redis** | Caching (planned) | 🚧 Roadmap |
| 🤖 **OpenAI API** | AI features (planned) | 🚧 Roadmap |

---

## ⚡ Metrics (Approximate)

```
~95%     Uptime (when the laptop is running)
~150ms   Latency (localhost is fast)
256-bit  Encryption (standard JWT)
24/7     Support (student Discord)
```

---

## ✨ Features (What Actually Works)

### 🔒 **Security (Following Best Practices)**

- **JWT with refresh tokens**: Stateless authentication, expirable tokens
- **Password hashing**: bcrypt with salt, no plaintext in DB
- **Protected routes**: Auth middleware on all sensitive routes
- **CORS configured**: No unauthorized cross-origin requests
- **Input validation**: Zod/Joi for payload validation
- **HTTPS ready**: Ready for deployment with SSL certificate

> ⚠️ *Not yet professionally audited, but all security tutorials were religiously followed.*

---

### ⚡ **Real-Time (Socket.IO That Holds Up)**

- **Instant messages**: Bidirectional WebSocket with Socket.IO
- **Typing indicators**: "X is typing..."
- **Online status**: Real-time user statuses
- **Auto-reconnection**: Heartbeat and retry logic built-in
- **Pagination**: Message history loaded progressively
- **Read receipts**: Read/unread messages

> 💡 *Tested with multiple simultaneous connections. No lag (for now).*

---

### 💬 **Messaging (The Essentials)**

- **Direct messages**: 1-to-1 conversations between users
- **Persistent history**: PostgreSQL to keep all messages
- **User search**: Find and add contacts
- **Friend system**: Friend requests (pending/accepted/blocked)
- **Custom avatars**: Upload + automatic WebP conversion
- **User cache**: Client-side performance optimization

> 🚧 *Group messages under development.*

---

### 🏗️ **Architecture (MVC Pattern)**

```
Frontend (React + Vite)
    ├── Custom Hooks (useSocket, useMessages, useAuth...)
    ├── Components (Messages, Friends, Profile...)
    ├── API Service Layer (axios + Socket.IO client)
    └── Type-safe with TypeScript

Backend (Node.js + Express)
    ├── Controllers (auth, user, direct, friend...)
    ├── Services (business logic + Prisma queries)
    ├── Middlewares (auth, validation, error handling)
    ├── Socket.IO Server (real-time events)
    └── Prisma ORM (migrations + type generation)

Database (PostgreSQL + Prisma)
    ├── User model (auth, profile, publicKey)
    ├── Message model (content, sender, receiver, timestamps)
    ├── Friendship model (relations, status)
    └── Versioned migrations
```

> 🎓 *Classic MVC architecture, no over-engineering. Clean and maintainable.*

---

### 🎨 **UI/UX (Homemade CSS)**

- **Custom design**: No UI lib, everything handmade in CSS Modules
- **Responsive**: Desktop optimized, mobile... coming soon
- **Dark mode**: Because we code at night
- **Smooth animations**: Clean CSS transitions
- **Auto-resizing textarea**: Comfort first
- **Resizable panels**: Adaptable interface

> 💅 *Inspired by Discord/Telegram, but built from scratch without Tailwind/MUI.*

---

### 💻 **DevOps (Handcrafted Scripts)**

- **Monorepo structure**: Client + Server + Shared types
- **Shell scripts**: `start-Discode.sh`, `kill-Discode.sh`, `reset-db.sh`
- **PID management**: Process tracking for dev
- **Prisma migrations**: DB schema versioning
- **Seed script**: Test data for development
- **Environment variables**: `.env` for configuration

> 🔧 *Not dockerized yet. It's on the roadmap.*

---

## 🔐 Security (What We've Implemented)

| Feature | Status | Description |
|---------|--------|-------------|
| 🔐 **JWT Auth** | ✅ Active | Access + refresh tokens |
| 🔒 **Password Hash** | ✅ Active | bcrypt with salt |
| 🛡️ **Input Validation** | ✅ Active | Zod schemas |
| 🚫 **Rate Limiting** | 🚧 Planned | Anti-spam protection |
| 🔑 **2FA** | 📋 Roadmap | Authenticator app |
| 🔐 **E2E Encryption** | 📋 Roadmap | Asymmetric encryption |
| 🔍 **Audit Logs** | 📋 Roadmap | Action traceability |

---

## 🗺️ Roadmap (Realistic)

### ✅ **Phase 1: MVP** (Done)
- [x] Complete JWT auth
- [x] Real-time direct messages
- [x] Friend system
- [x] Avatar upload
- [x] Clean React interface

**Q1 2025** - *Goal achieved!*

---

### 🚧 **Phase 2: Core Features** (In Progress)
- [ ] Group messages
- [ ] Rate limiting
- [ ] Content moderation
- [ ] Push notifications
- [ ] Advanced search

**Q2-Q3 2025** - *Work in progress*

---

### 🔮 **Phase 3: Advanced** (Planned)
- [ ] Redis for caching
- [ ] AI for suggestions/moderation
- [ ] E2E encryption
- [ ] Voice/video calls (WebRTC)
- [ ] File sharing
- [ ] Emojis and reactions

**Q4 2025 - 2026** - *If time permits*

---

### 🌍 **Phase 4: Scale** (Ambitious)
- [ ] Docker + Kubernetes
- [ ] CDN for assets
- [ ] Multi-region
- [ ] Public API
- [ ] Mobile app (React Native)
- [ ] i18n (multi-language)

**2026+** - *Dreaming a bit*

---

## 🤔 Honest FAQ

### **Why not Discord/Slack?**
> It's a learning project. The goal is to understand how it works under the hood.

### **Is it secure?**
> Basic standards are respected (JWT, bcrypt, HTTPS). But not professionally audited yet.

### **Why no UI framework?**
> To learn CSS and truly understand React. No unnecessary dependencies.

### **Is it scalable?**
> For a few hundred users, yes. For millions... we'll see later.

### **Why PostgreSQL and not MongoDB?**
> Because messaging is relational by nature. Users ↔ Messages ↔ Friends.

### **What's the AI for?**
> Content moderation, reply suggestions, conversation summaries. But not implemented yet.

---

## 📊 Project Stats

```
📁 Lines of code      : ~15,000+ (client + server)
⏱️ Dev time           : ~4 months (part-time)
🐛 Known bugs         : 12 (and we find more every day)
☕ Coffees consumed   : Too many to count
🌙 All-nighters       : A few
📚 Tutorials followed : ~50+ (YouTube, docs, Stack Overflow)
```

---

## 🎓 What I Learned

- **WebSocket**: Socket.IO and real-time management
- **Modern auth**: JWT, refresh tokens, security best practices
- **Backend architecture**: MVC, services layer, clean code
- **Database design**: Prisma, migrations, relations
- **Advanced React**: Custom hooks, context, optimization
- **TypeScript**: Full-stack typing, shared types
- **DevOps basics**: Scripts, env management, deployment

---

## 💡 Why Open Source?

Because I learn in public. The code isn't perfect, but it's documented and commented. If it can help other students, even better!

---

## 🚀 Want to Try?

**Demo**: [Discode-demo.example.com](#) *(coming soon)*  
**Code**: [GitHub - Discode](#)  
**Contact**: [Discord](#) • [Email](#)

---

## 📝 License

**MIT License** - Made with ❤️ by a learning student.

---

*"The best code is the one you understand." - Me, after 3 hours of debugging*

© 2025 Discode • Student project by Mohamed El Amine Y. • Looking for internship April 2026

[⭐ Star on GitHub](#) if you like the project!

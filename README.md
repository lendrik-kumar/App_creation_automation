# 🧩 NodeForge — Express App Generator

**NodeForge** is a powerful CLI toolkit that scaffolds a modern **Node.js + Express** application with a complete service architecture and production-ready configuration out of the box.

It bootstraps your project with best-practice tooling so you can start building features immediately.

---

## ✨ Features

✔ Express.js application scaffold  
✔ Modular service-based architecture  
✔ Redis-powered dependency & service manager  
✔ MongoDB integration  
✔ Docker-ready setup  
✔ GraphQL support  
✔ ESLint & TypeScript configuration  
✔ Centralized logging system  
✔ Global error handling  
✔ Automatic import management  

---

## 🧱 Included Services

| Service | Description |
|--------|-------------|
| **Basefile Service** | Project bootstrap & base configuration loader |
| **Dependency Service** | Central dependency injection & service registry |
| **Project Directory Service** | Project path & structure manager |
| **Docker Service** | Docker configuration & container support |
| **MongoDB Service** | Database connection & lifecycle management |
| **Logging Service** | Centralized logging system |
| **Error Handler Service** | Global error handling & crash management |
| **GraphQL Service** | GraphQL server configuration & startup |
| **ESLint Service** | Linting configuration & code quality enforcement |
| **TypeScript Config Service** | TypeScript compiler configuration generator |
| **Import Lines Service** | Automatic import formatting & organization |

---

## 🧰 Prerequisites

### Redis (Required)

NodeForge uses **Redis** for dependency resolution and internal service coordination.  
Make sure Redis is running locally on **port 6379** before using the toolkit.

---

### 🍎 macOS

```bash
brew install redis
brew services start redis
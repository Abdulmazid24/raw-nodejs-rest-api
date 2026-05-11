# 🚀 Raw Node.js REST API Architecture

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

A professional, modular REST API built entirely from scratch using **Raw Node.js (`http` module)** and **TypeScript**. This project demonstrates "Under the Hood" backend architecture without relying on frameworks like Express or Fastify.

## ✨ Key Features
- **No Frameworks:** Complete implementation using Node's core `http` module.
- **Event-Driven:** Custom request body parsing handling streams (`data` and `end` events).
- **TypeScript Ready:** Fully typed interfaces, strict configuration, and robust error handling.
- **Modular Architecture:** Clear separation of concerns (Routes, Controllers, Services, Utilities).
- **CRUD Operations:** Full Create, Read, Update, and Delete functionality using a simulated file-system database.

## 📂 Project Structure
```text
src/
├── config/           # Environment variables management
├── controllers/      # Core business logic & request handling
├── database/         # JSON-based simulated database
├── routes/           # Request routing and URL parsing
├── services/         # File system operations (I/O)
├── types/            # TypeScript interfaces and types
├── utility/          # Reusable functions (Body parsing, Response formatting)
└── server.ts         # Application entry point
```

## 🛠️ Getting Started

### Prerequisites
- Node.js (v20+ recommended)
- npm or yarn

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/raw-nodejs-rest-api.git
cd raw-nodejs-rest-api
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=3000
```

4. Start the development server:
```bash
npm run dev
```

The server will start at `http://localhost:3000`.

## 📌 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | `/products` | Get all products |
| GET    | `/products/:id` | Get a specific product by ID |
| POST   | `/products` | Create a new product |
| PUT    | `/products/:id` | Update an existing product |
| DELETE | `/products/:id` | Delete a product |

## 👨‍💻 Author

**Abdul Mazid**
- 🌐 **Portfolio:** [abdulmazid-portfolio.vercel.app](https://abdulmazid-portfolio.vercel.app/)
- 💼 **LinkedIn:** [Abdul Mazid](https://www.linkedin.com/in/abdul-maziddev/)
- 📧 **Email:** abdulmazid.dev@gmail.com

---
*If you find this project helpful for learning Raw Node.js concepts, feel free to give it a ⭐️!*

<h1 align="center">🛒 Cartly — Modern E-Commerce Platform</h1>

<p align="center">
  <strong>A modern, responsive and scalable e-commerce platform built for a smooth online shopping experience.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Vite-7.x-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/TypeScript-Supported-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

---

## 📖 About Cartly

**Cartly** is a modern full-stack e-commerce platform designed to provide users with a clean, responsive and intuitive online shopping experience.

The platform combines a fast React-based frontend with a scalable backend architecture, database management and API-driven services.

Cartly is designed around a simple goal:

> **Make online shopping fast, simple and enjoyable.**

The project includes product browsing, product details, shopping cart functionality, user interactions and a structured backend architecture for managing application data.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🛍️ **Product Browsing** | Browse and explore products through a clean and responsive interface. |
| 🔎 **Product Discovery** | Search and discover products easily. |
| 📦 **Product Details** | View detailed information about individual products. |
| 🛒 **Shopping Cart** | Add, remove and manage products in the shopping cart. |
| 📱 **Responsive Design** | Optimized for desktop, tablet and mobile devices. |
| ⚡ **Fast Performance** | Built with Vite for a fast development and production experience. |
| 🔗 **API Integration** | Communicates with the backend through REST APIs. |
| 🔐 **Authentication Ready** | Architecture prepared for secure user authentication and authorization. |
| 💾 **Database Integration** | Backend data is managed using Prisma and MongoDB. |
| 🧩 **Modular Architecture** | Components and features are organized for maintainability and scalability. |
| 🎨 **Modern UI** | Clean and modern interface designed for an e-commerce experience. |

---

## 🏗️ Project Architecture

Cartly is structured as a full-stack application:

```text
        ┌──────────────────────┐
        │      Cartly UI       │
        │     React + Vite     │
        └──────────┬───────────┘
                   │
                   │  REST API
                   ▼
        ┌──────────────────────┐
        │   Cartly Backend     │
        │ Node.js / API Layer  │
        └──────────┬───────────┘
                   │
                   │  Prisma ORM
                   ▼
        ┌──────────────────────┐
        │       MongoDB        │
        │       Database       │
        └──────────────────────┘
```

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React, Vite, JavaScript (ES6+), TypeScript support |
| **Backend** | Node.js, REST APIs |
| **ORM** | Prisma |
| **Database** | MongoDB |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [MongoDB](https://www.mongodb.com/) instance (local or Atlas)
- npm or yarn

### Step 1 — Clone the Repository

```bash
git clone https://github.com/HelloWorld-Farhan/<your-repo-name>.git
cd <your-repo-name>
```

### Step 2 — Install Dependencies

```bash
npm install
```

### Step 3 — Configure Environment Variables

Create a `.env` file in the backend directory:

```env
DATABASE_URL="your_mongodb_connection_string"
PORT=5000
```

### Step 4 — Set Up Prisma

```bash
npx prisma generate
npx prisma db push
```

### Step 5 — Run the App

```bash
npm run dev
```

### Step 6 — Build for Production

```bash
npm run build
```

---

## 👨‍💻 Author

**Farhan Khalid**

📧 [farhankhalid17968@gmail.com](mailto:farhankhalid17968@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/farhan-khalid-117514259/)
🐙 [GitHub](https://github.com/HelloWorld-Farhan)

---

## 🌟 Support

If you like this project, please consider giving it a ⭐ on GitHub!

<p align="center">Made with ❤️ in India</p>

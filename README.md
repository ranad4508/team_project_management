# 🌐 WorkSphere

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Build Status](https://img.shields.io/github/actions/workflow/status/yourusername/worksphere/build.yml?branch=main)](https://github.com/yourusername/worksphere/actions)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Node Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

<p align="center">
  <strong>Enterprise-Grade Project Management Solution Built with Modern Tech Stack</strong>
</p>

[Demo](https://demo.worksphere.com) • [Documentation](https://docs.worksphere.com) • [Report Bug](https://github.com/yourusername/worksphere/issues) • [Request Feature](https://github.com/yourusername/worksphere/issues)

![Project Demo](docs/assets/demo.gif)

</div>

---

## 📌 Overview

**WorkSphere** is a robust project management platform built using the MERN stack and TypeScript. It helps teams manage their workflow and boost productivity with:

- 🔄 Real-time project tracking
- 👥 Workspace-based collaboration
- 📊 Visual analytics
- ✅ Task prioritization
- 🔐 Role-based access control

---

## 📑 Table of Contents

- [Quick Start](#-quick-start)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Environment Setup](#-environment-setup)
- [Security](#-security)
- [Troubleshooting](#-troubleshooting)
- [License](#-license)

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/ranad4508/team_project_management.git

# Navigate to backend or frontend folder
cd backend

# Install dependencies
npm install

# Start the development server
npm run dev
```

---

## ⚡ Features

### Project & Workspace Management

- Create & manage multiple workspaces
- Use templates for faster setup
- Define custom workflows
- Allocate team resources efficiently

### Task & Sprint Management

- Sprint planning and backlog grooming
- Assign and track tasks
- Track task dependencies

### Real-Time Collaboration

- Instant updates across devices
- Activity tracking and notifications

---

## 💻 Tech Stack

| Layer        | Technology                                  |
| ------------ | ------------------------------------------- |
| **Backend**  | **Node.js**, **Express.js**, **TypeScript** |
| **Frontend** | **React.js**, **Vite.js**, **TypeScript**   |
| **UI/UX**    | **Tailwind CSS**, **Shadcn UI**             |
| **Database** | **MongoDB**, **Mongoose**                   |
| **Auth**     | **Google OAuth**, **JWT**, **Cookies**      |

---

## 🛠 Installation

### Prerequisites

- Node.js `>= 16.x`
- npm `>= 8.x`
- MongoDB `>= 5.0`

### Setup

```bash
# Install global tools
npm install -g typescript ts-node pm2

# Clone and configure
git clone https://github.com/ranad4508/team_project_management.git
cd worksphere
cp .env.example .env

# Install project dependencies
npm install

# Run migrations if needed
npm run migrate
```

---

## ⚙️ Environment Setup

```env
# Server
NODE_ENV=development
PORT=8000
API_VERSION=v1
CORS_ORIGIN=http://localhost:3000

# MongoDB
MONGODB_URI=mongodb://localhost:27017/worksphere

# Authentication
JWT_SECRET=your-super-secret-key
JWT_EXPIRES_IN=7d
SESSION_SECRET=session-secret

# OAuth
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret

# Redis (optional)
REDIS_URL=redis://localhost:6379

# Monitoring (optional)
SENTRY_DSN=your-sentry-dsn
```

---

## 🔒 Security

- ✅ JWT with HttpOnly cookies
- ✅ Bcrypt for password hashing
- ✅ CORS, Helmet, and Rate Limiting
- ✅ CSRF & XSS Protection
- ✅ Field-level encryption in sensitive DB models

---

---

## ❗ Troubleshooting

```bash
# Health check
npm run health-check

# Reset MongoDB
npm run db:reset
```

---

## 📜 License

Copyright © 2023  
[Dinesh Kumar Rana](https://github.com/ranad4508)  
Licensed under the [MIT License](LICENSE)

---

<div align="center">
  <p>If you found this project helpful, please give it a ⭐</p>
  <a href="https://github.com/yourusername/worksphere/stargazers">
    <img src="https://reporoster.com/stars/yourusername/worksphere" alt="Stargazers"/>
  </a>
</div>

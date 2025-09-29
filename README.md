# ELITE-CAREER
A full-stack, AI-powered platform for professional career document writing services, built with Docker, Node.js, Express, and Vanilla JS.

EliteCareer - AI-Powered Career Services Platform
A state-of-the-art, global platform for a premium, human-powered career document writing service, enriched with cutting-edge AI tools. This repository contains the full-stack code for a complete, enterprise-grade application, from the public-facing website to the secure client, writer, and admin portals.


Project Status
This project is a comprehensive showcase of a full-stack application. The code is made public for demonstration and portfolio purposes. At this time, the repository is not open to external contributions.

Key Features
AI-Powered Analysis: Free, instant CV review tool using the Google Gemini API to provide a score and actionable feedback.

Dedicated User Portals:

Client Dashboard: Manage orders, communicate directly with writers, and download final documents.

Writer Dashboard: View and accept assigned orders, manage workload, and communicate with clients.

Admin Dashboard: Full oversight of the platform with CRUD functionality for users, orders, and content.

Content & Resource Hub: A complete blog system to establish thought leadership and drive SEO.

Secure & Scalable:

Authentication: JWT-based authentication with secure password hashing (bcryptjs).

Role-Based Access Control (RBAC): Distinct middleware secures routes for clients, writers, and admins.

Enterprise-Grade Security: Includes security headers (helmet) and rate-limiting to prevent common attacks.

Containerized: A Dockerfile is included for easy, consistent deployment.

Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Authentication: JSON Web Tokens (JWT)

File Handling: Multer

External APIs: Google Gemini API

DevOps: Docker, GitHub Actions (for CI/CD)

Project Structure
The project is organized into two main directories: backend for the server-side application and public for all client-facing static files.

elite-career-platform/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── .env.example
│   ├── Dockerfile
│   ├── package.json
│   └── server.js
│
├── public/
│   ├── css/
│   ├── js/
│   ├── index.html
│   └── ... (other html files)
│
└── README.md


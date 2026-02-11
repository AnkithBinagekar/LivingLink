
# LivingLink

## Project Title
LivingLink

LivingLink is a modern residential society management platform that connects residents, staff, and committee members through a single, easy to use website. It offers digital notices, online payment of dues, facility booking, complaint tracking, visitor management, and transparent financial records.LivingLink ensures smooth operations and a more organized community life.

## Live Demo

Frontend (Vercel):
[https://your-vercel-url.vercel.app](https://living-link.vercel.app/)

Backend API (Render):
https://livinglink.onrender.com

Swagger API Docs:
https://livinglink.onrender.com/api-docs

## Architecture
React Frontend (Vercel)
        ↓
Node.js + Express API (Render)
        ↓
MongoDB Atlas (Cloud Database)

## Table of Contents
1. [About The Project](#about-the-project)
2. [Key Features](#key-features)
3.  [Tech Stack](#tech-stack)
4.  [Installation Setup](#installation-setup)
5.  [Screenshots](#screenshots)
6.   [License](#license)

## About The Project
LivingLink replaces outdated manual and paper-based society management processes with a centralized digital platform. It improves communication, transparency, and efficiency by providing a single system for all residential society operations.

The platform supports multiple roles such as residents, secretaries, treasurers, security guards, and maintenance staff with role-based access control.

## Key Features
- JWT-based authentication and role-based authorization

- Digital notice board for announcements

- Visitor management and approval system

- Complaint registration and tracking

- Facility booking system

- Online maintenance dues payment

- Transparent financial records

- Member and staff directory

- Swagger API documentation

## Tech Stack
This project is built using modern web technologies:

Frontend:
- React.js
- Next.js
- Tailwind CSS

Backend:
- Node.js
- Express.js

Database:
- MongoDB
- Mongoose

Authentication:
- JSON Web Tokens (JWT)
- bcrypt password hashing

Deployment:
- Vercel (Frontend)
- Render (Backend)

## Installation Setup
### 1. Clone the repository
git clone https://github.com/AnkithBinagekar/LivingLink.git

cd LivingLink

### 2. Install dependencies
npm install

### 3. Set up environment variables
Create a .env file in the root directory with the following variables:
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000

### 4. Start the development server
npm run dev

### 5. Access the application
Open your browser and navigate to http://localhost:3000

## Screenshots

#### Landing Page
<img width="1901" height="939" alt="image" src="https://github.com/user-attachments/assets/c44dfb81-2aad-43bd-a441-243a1d59e696" />

#### Login Page
<img width="1897" height="934" alt="image" src="https://github.com/user-attachments/assets/eb28b26a-f027-4ee3-afa6-77f00e476fa5" />

#### Residents Dashboard
<img width="1896" height="672" alt="image" src="https://github.com/user-attachments/assets/7cc9b503-26c7-4edb-a89e-9e3d9964775e" />

### Secratary Dashboard
<img width="1901" height="868" alt="image" src="https://github.com/user-attachments/assets/0d9c1fce-c5a1-452b-996d-c50578dc082b" />

#### Security Dashboard
<img width="1901" height="453" alt="image" src="https://github.com/user-attachments/assets/dc7979da-5a81-4c46-90cb-1e32139188fd" />

#### Treasurer Dashboard
<img width="1899" height="925" alt="image" src="https://github.com/user-attachments/assets/46895aa3-e948-404f-877f-62a393d2329a" />

#### Maintenance Staff Dashboard
<img width="1900" height="482" alt="image" src="https://github.com/user-attachments/assets/c35f194e-1d1d-42b6-a2fd-74ccb91fdedb" />


  








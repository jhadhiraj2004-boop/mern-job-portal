# MERN Job Portal

A **full-stack job portal platform** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.
The platform allows **job seekers to search and apply for jobs** while **recruiters can post and manage job openings** through a dedicated dashboard.

---

## Features

* User authentication using **Clerk**
* Job search and job application system
* Resume upload for job seekers
* Recruiter dashboard to post and manage jobs
* Accept or reject job applications
* Error tracking and monitoring using **Sentry**
* Full-stack architecture using **MongoDB, Express, React, Node**

---

# Project Structure

```
mern-job-portal
│
├── client        # React frontend
├── server        # Node.js + Express backend
└── README.md
```

---

# Installation

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/mern-job-portal.git
cd mern-job-portal
```

---

### 2. Install backend dependencies

```
cd server
npm install
```

Create a `.env` file inside **server/**

Example:

```
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
SENTRY_DSN=your_sentry_dsn
PORT=5000
```

Run backend server:

```
npm run dev
```

or

```
node server.js
```

Backend will run on:

```
http://localhost:5000
```

---

### 3. Install frontend dependencies

Open another terminal and run:

```
cd client
npm install
```

Create `.env` inside **client/**

Example:

```
VITE_API_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

Run frontend:

```
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

# Deployment / Hosting

## Frontend Deployment (Vercel)

1. Push project to GitHub
2. Go to **https://vercel.com**
3. Import the GitHub repository
4. Select the **client** folder as the root directory
5. Add environment variables in Vercel

Deploy.

Your frontend will be hosted online.

---

## Backend Deployment Options

### Option 1: Render (Recommended)

1. Go to **https://render.com**
2. Create new **Web Service**
3. Connect your GitHub repository
4. Select **server folder**
5. Add environment variables

Deploy.

---

### Option 2: Railway

1. Go to **https://railway.app**
2. Connect GitHub repository
3. Deploy the **server** folder
4. Add environment variables

---

# Tech Stack

Frontend

* React.js
* Tailwind CSS
* Vite

Backend

* Node.js
* Express.js

Database

* MongoDB

Authentication

* Clerk

Monitoring

* Sentry

---

# Author

**Dhiraj Kumar**

LinkedIn
GitHub

---

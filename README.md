# MERN Job Portal

A full-stack **Job Portal Platform** built with the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
The application allows **job seekers to search and apply for jobs** while **recruiters can post and manage job listings through a dashboard**.

---

# Features

* User authentication using **Clerk**
* Job search and job application system
* Resume upload functionality
* Recruiter dashboard for managing job posts
* Accept or reject job applications
* Error monitoring using **Sentry**
* Image upload support using **Cloudinary**

---

# Tech Stack

Frontend

* React.js
* Vite
* Tailwind CSS

Backend

* Node.js
* Express.js

Database

* MongoDB Atlas

Authentication

* Clerk

Monitoring

* Sentry

Image Storage

* Cloudinary

---

# Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/mern-job-portal.git
cd mern-job-portal
```

---

# Backend Setup (Server)

Navigate to the server folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the **server** folder and add:

```
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
SENTRY_DSN=your_sentry_dsn
PORT=5000
```

Start the backend server:

```bash
npm run dev
```

Backend will run at:

```
http://localhost:5000
```

---

# Frontend Setup (Client)

Open another terminal and navigate to the client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Create `.env` inside **client** folder:

```
VITE_API_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

Run the frontend:

```bash
npm run dev
```

Frontend will run at:

```
http://localhost:5173
```

---

# Deployment

## Deploy Backend

You can deploy the backend using:

* Vercel
* Render
* Railway

Steps:

1. Push the project to GitHub
2. Connect repository to hosting platform
3. Add environment variables
4. Deploy the server

---

## Deploy Frontend

Deploy frontend using **Vercel**.

Steps:

1. Connect GitHub repository
2. Select the **client** folder
3. Add environment variables
4. Deploy

---

# Author

Dhiraj Kumar
Electronics & Communication Engineering
Full Stack Developer

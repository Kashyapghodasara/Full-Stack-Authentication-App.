# Full-Stack Authentication App

This is a full-stack authentication app built with **Next.js**, **React.js**, and **TypeScript**. The app uses **bcrypt** for password hashing, **JWT** for authentication and authorization, and stores user data in **MongoDB**.

-----------------------------------------------------------------------------------------------------------------------------


## Features

- 🔐 User authentication (Sign Up & Login)
- 🔑 Password encryption with bcrypt
- 🛡️ Secure authentication & authorization with JWT
- 💾 Data persistence using MongoDB

---

## Installation Guide

Follow the steps below to set up the project locally.
2. Install Dependencies
Install the required packages:


```
npm install
```

## Set Up Environment Variables
Create a .env.local file in the root of your project and add the following:


## MongoDB connection string
```MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority```

## JWT Secret Key
```JWT_SECRET=your_jwt_secret_key```

## Run the Development Server
Start the server with the following command:


```npm run dev```
Navigate to ```http://localhost:3000``` to see the application.

## Tech Stack
Frontend: Next.js, React.js, TypeScript<br>
Backend: Next.js API Routes<br>
Authentication: bcrypt, JWT<br>
Database: MongoDB


## Scripts
```npm run dev``` – Runs the app in development mode.<br>
```npm run build``` – Builds the app for production.<br>
```npm start ```– Runs the built app in production mode.

License
This project is licensed under the MIT License.


### Key Sections:
- **Installation Guide:** Provides a step-by-step guide to set up the project.
- **Tech Stack:** Lists technologies used.
- **Scripts:** Lists available npm scripts.
- **Environment Variables:** Explains how to set up necessary environment variables.

Feel free to modify it according to your project needs! 😊










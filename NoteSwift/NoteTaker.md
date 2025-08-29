# NoteTaker Application

## Overview

NoteTaker is a web app that lets you create, save, and manage personal notes.
It has a React frontend and an Express.js backend. The app has login/signup with email and Google, OTP email verification, and a nice responsive design using Tailwind CSS and shadcn/ui components.

## How It’s Built

### Frontend

* **React + TypeScript** → for building the UI
* **Tailwind CSS + shadcn/ui** → for styling and ready-made components
* **TanStack Query** → for handling API data and caching
* **Wouter** → for simple routing
* **React Hook Form + Zod** → for forms and input validation
* **Vite** → for running locally and building the app for production

### Backend

* **Node.js + Express.js** → server for APIs
* **TypeScript** → used everywhere so code is safer
* **JWT** → for login sessions
* **bcrypt** → for password hashing
* **Nodemailer** → to send OTP verification emails
* **REST API** → with proper error handling and logging

### Database

* **MongoDB Atlas** (cloud database)
* **Mongoose** → to define schemas and interact with MongoDB

### Authentication

* **Email + Password** login with JWT tokens
* **OTP Email Verification** → users get a code in their email to confirm account
* **Google Login (OAuth)** → quick login with Google
* **Security** → passwords hashed, protected routes, verified tokens

### Development Setup

* **Shared types** → frontend and backend can use the same schemas
* **Hot Reload** → frontend changes show up instantly with Vite
* **Path Aliases** → cleaner imports like `@/` and `@shared/`
* **Error Handling** → proper error messages + runtime overlay in dev

## Libraries & Tools Used

### Frontend

* React, React DOM
* React Hook Form
* TanStack Query
* Wouter
* Tailwind CSS, shadcn/ui
* Lucide React (icons)
* Google Fonts (Inter, DM Sans, Fira Code, etc.)

### Backend

* Express.js
* Mongoose (MongoDB Atlas connection)
* jsonwebtoken
* bcrypt
* nodemailer

### Development

* Vite + esbuild for builds
* TypeScript for type safety
* Zod for validation

---

<h1 align="center">🍽️ Saadibou</h1>

<h3 align="center">
Full-Stack Restaurant Ordering Platform
</h3>

<p align="center">
  React • Node.js • Express • MongoDB • Stripe
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 📌 Overview

A full-stack food ordering platform for a Tunisian restaurant, made of a customer storefront, an admin dashboard and a REST API. Built in April 2025.

<<BACKGROUND LINE>>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 🎬 Demo

<p align="center">
  ▶️ A full 8-minute video demo of the platform is coming soon.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## ✨ Features

### 🛒 Customer app
- 🍴 Browse the menu by category and search dishes
- 🧺 Cart management
- 🔐 Sign up and log in (JWT authentication)
- 💳 Place an order and pay online with Stripe
- 📦 Order history ("My Orders")

### 🛡️ Admin dashboard
- ➕ Add new dishes with an image upload
- 📋 List and remove dishes
- 📦 View and manage customer orders

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 🛠️ Tech Stack

**Architecture**

`React (Vite)` → `Express REST API` → `MongoDB`

**Tech Stack**

`React` · `Vite` · `Node.js` · `Express.js` · `MongoDB` · `Mongoose` · `JWT` · `Stripe`

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 📁 Project Structure

```
Saadibou-food/
├── frontend/   # customer storefront (React + Vite)
├── admin/      # admin dashboard (React + Vite)
└── backend/    # REST API (Node.js + Express + MongoDB)
    └── uploads/  # dish images
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>



<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- A MongoDB database (for example a free MongoDB Atlas cluster)
- A Stripe account (test mode is enough)

### 1. Backend

```bash
cd backend
npm install
```

Copy `.env.example` to `.env` and fill in your own values:

```
JWT_SECRET=
STRIPE_SECRET_KEY=
MONGO_URI=
```

Start the server:

```bash
npm run dev
```

### 2. Frontend

```bash
cd frontend
npm install
npm run dev
```

### 3. Admin

```bash
cd admin
npm install
npm run dev
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=00BFFF&height=2&section=header" width="80%">
</p>

## 👨‍💻 Author

**Med Amine Mrad**, Software Engineering student at ITBS, Tunisia.

<p align="center">
  <a href="https://www.linkedin.com/in/mrad-mohamed-amine">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:mohamedamine.mrad@itbs.tn">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>

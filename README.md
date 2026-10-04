# Saadibou: Food Delivery Web App

A full-stack food ordering platform for a Tunisian restaurant, with a customer storefront, an admin dashboard, and a REST API. Built in April 2025.

## Features

**Customer app (`frontend`)**
- Browse the menu by category and search dishes
- Cart management
- Sign up / log in (JWT authentication)
- Place an order and pay online with Stripe
- Order history ("My Orders")

**Admin dashboard (`admin`)**
- Add new dishes with an image upload
- List and remove dishes
- View and manage customer orders

## Tech Stack

- **Frontend / Admin:** React, Vite
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Auth:** JWT
- **Payments:** Stripe

## Project Structure

```
Saadibou-food/
├── frontend/   # customer storefront (React + Vite)
├── admin/      # admin dashboard (React + Vite)
└── backend/    # REST API (Node.js + Express + MongoDB)
    └── uploads/  # dish images
```

## Getting Started

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
MONGO_URI=
JWT_SECRET=
STRIPE_SECRET_KEY=
```

Start the server:

```bash
<<BACKEND START COMMAND>>
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

## Background

<<BACKGROUND LINE>>

## Author

Med Amine Mrad: Software Engineering student at ITBS, Tunisia.

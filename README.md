# PixelForge - Elite Creative Agency Website 🚀

This project is a High-End Landing Page for a Creative Digital Agency.

==a compny that create websites, ui design, marketing, so that compne need a website to show case wwhwat works they done  

💼 What is the Purpose?

showcasing our works
The purpose of this site is to sell professional services (like website design, branding, and marketing) to other businesses.

Imagine you are running a fancy agency called PixelForge Studio. You need a website that makes potential clients look at your screen and say:

"Wow, these guys are expensive and brilliant. I want them to build my website."

A high-end, cinematic landing page designed for a fictional creative digital agency. This project was built to showcase advanced frontend capabilities, interactive UI design, and premium user experience.



## 🎯 Purpose
To act as a "Showroom" for a professional agency, commanding premium rates through polished motion design, intuitive interactions, and a cinematic feel.

## 🛠 Tech Stack
* **React.js (Vite):** Fast, modern frontend framework.
* **Tailwind CSS:** Modern utility-first CSS styling.
* **Framer Motion:** Advanced animation library for staggering and scroll-based motion.
* **Lenis Scroll:** For butter-smooth momentum scrolling.
* **React Icons:** High-quality vector icons.

## ✨ Key Features
* **Magnetic Cursor & Button:** Custom cursor that interacts with UI elements and buttons that pull towards the mouse.
* **Staggered Entrance Animations:** Premium reveal effects on load.
* **Scroll-Triggered Counters:** Data visualizations that animate only when in view.
* **Smooth Scroll Momentum:** Lenis integration for a high-end browsing experience.
* **Smart Navigation:** Hides on scroll-down, appears on scroll-up.




# 🏢 ANZIL — Premium Digital Agency Website

A full-stack MERN application for a premium digital agency.

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- MongoDB (local or Atlas)

### 1. Start Backend
```bash
cd backend
npm install
npm run dev
```
Backend runs at: http://localhost:5000

### 2. Start Frontend
```bash
cd frontend
npm install
npm start
```
Frontend runs at: http://localhost:3000

## 🔐 Admin Access
- URL: http://localhost:3000/admin/login
- Username: **admin**
- Password: **admin**

## 📁 Project Structure
```
anzil-agency/
├── backend/
│   ├── models/          # MongoDB schemas
│   ├── routes/          # Express API routes
│   ├── middleware/      # Auth middleware
│   ├── seedData.js      # Initial data seeder
│   └── server.js        # Entry point
└── frontend/
    ├── src/
    │   ├── components/  # Navbar, Footer
    │   ├── pages/       # All page components
    │   ├── context/     # Auth context
    │   └── utils/       # API helpers
    └── public/
```

## 🛠 Tech Stack
- **Frontend**: React 18, React Router 6, Framer Motion, Axios
- **Backend**: Express.js, Mongoose, JWT, bcryptjs
- **Database**: MongoDB

## 🌐 Pages
- `/` — Home with hero, services, testimonials
- `/services` — All agency services
- `/portfolio` — Filterable portfolio grid
- `/case-studies` — Detailed project case studies
- `/blog` — Blog with category filter
- `/blog/:id` — Individual blog post
- `/contact` — Contact form
- `/admin` — Protected admin dashboard

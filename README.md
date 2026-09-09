<div align="center">

# 🌿 Botaniq — Full-Stack Skincare E-Commerce Platform

### 🚀 An Engineering Showcase by **Jvke**

[![Portfolio](https://img.shields.io/badge/Portfolio-jvke--dev.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jvke-dev.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Piseth--007-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Piseth-007)
[![LinkedIn](https://img.shields.io/badge/Connect-Jvke-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://jvke-dev.vercel.app/)

<p align="center">
  <b>A production-grade, editorial botanical skincare commerce ecosystem built with a decoupled architecture.</b><br>
  Engineered with high aesthetic standards, real-time localized payments, and cloud automation.
</p>

---

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_11-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Google OAuth](https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=flat-square&logo=google&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary_CDN-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_Alerts-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Bakong KHQR](https://img.shields.io/badge/Bakong_KHQR-E1251B?style=flat-square&logo=contactlesspayment&logoColor=white)

</div>

---

## 👨‍💻 Meet the Developer

> **"Bridging technical scalability with tactile, editorial design."**

Hi! I'm **Jvke** — a passionate **Software Engineer, engineering student, and Full-Stack Developer**. I specialize in engineering modern web applications that don't just work reliably under the hood, but also deliver fluid, memorable user experiences.

- 🌐 **Live Portfolio:** [jvke-dev.vercel.app](https://jvke-dev.vercel.app/)
- 💻 **Core Specialties:** Modern React ecosystems, RESTful backend architecture with Laravel & Node, database design, localized payment gateways, and cloud asset management.
- 🎯 **Philosophy:** Code architecture should be clean, secure, and decoupled — while design should feel intentional, responsive, and human.

---

## 📖 Project Concept: Why Botaniq?

Most e-commerce starter templates stop at basic cart manipulation and static mockups. **Botaniq** was built to push the boundary of a full-scale commercial platform:

1. **Editorial Brand Identity:** Tailored specifically for organic botanical skincare, balancing serif typography (_Fraunces_), warm paper textures, and responsive geometric layouts.
2. **True Enterprise Decoupling:** Complete separation of concerns between a **React 19 SPA** frontend and a **Laravel REST API** backend secured by Sanctum Bearer tokens.
3. **Localized Real-World Commerce:** Directly integrated with **Bakong KHQR (Cambodia EMVCo standard)** and **ABA PayWay**, allowing instant mobile banking transactions.
4. **Autonomous Store Operations:** Real-time push notifications sent to the store owner's **Telegram** upon successful order placement, paired with high-fidelity printable thermal receipts.

---

## 🏛️ System Architecture

```text
  ┌────────────────────────────────────────────────────────┐
  │                 Client / Browser View                  │
  └──────────────────────────┬─────────────────────────────┘
                             │  (User Interactions & State)
                             ▼
  ┌────────────────────────────────────────────────────────┐
  │         Frontend: React 19 + Vite + Tailwind CSS        │
  │     • Framer Motion Transitions    • Recharts Analytics│
  │     • Dynamic KHQR Generator       • Responsive Split  │
  └──────────────────────────┬─────────────────────────────┘
                             │  HTTPS / REST API (Sanctum Tokens)
                             ▼
  ┌────────────────────────────────────────────────────────┐
  │           Backend: Laravel 11 RESTful Engine           │
  │     • Resource Controllers         • Form Requests & DB│
  │     • Custom Email OTP Engine      • Order State Mach. │
  └─────────┬─────────────┬─────────────┬─────────────┬────┘
            │             │             │             │
            ▼             ▼             ▼             ▼
      ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐
      │   MySQL   │ │ Cloudinary│ │  Bakong   │ │ Telegram  │
      │ Database  │ │ Media CDN │ │ KHQR / ABA│ │ Bot Alerts│
      └───────────┘ └───────────┘ └───────────┘ └───────────┘
```

---

## 🌟 Key Technical Highlights

### 1. 🔐 Dual Authentication & 6-Digit Email OTP

- **Google OAuth 2.0 Integration:** 1-Click authentication using Google Identity Services (GIS) with secure backend JWT ID token verification.
- **Custom OTP Verification:** Built-in email OTP verification using custom Laravel Mailables, preventing bot signups and unverified email persistence.
- **Anti-Clipping Split Auth Shell:** Ergonomic 50/50 responsive layout featuring brand photography and floating customer trust badges.

### 2. 🛍️ Customer Experience & Dynamic Catalog

- **Instant Search & Multi-Faceted Filters:** Filter by category, skincare brand, and price ranges with zero layout shifts.
- **Optimized UI States:** Smooth skeleton reloaders during catalog queries and friendly empty-state recovery fallbacks.
- **Comprehensive Product Profiles:** High-res Cloudinary image zoom, ingredient breakdown, skin-suitability badges, and customer reviews.

### 3. 💳 Localized Payment Processing (Cambodia)

- **Dynamic Bakong KHQR:** Generates compliant EMVCo QR codes on the fly in both USD and KHR currencies.
- **Automated Payment Polling:** Real-time client polling verifying transaction status against the national banking gateway.
- **ABA PayWay Sandbox Flow:** Ready-to-deploy digital card & merchant checkout pipeline.

### 4. ⚡ Admin Suite & Operational Automation

- **Real-Time Analytics Dashboard:** Interactive revenue curves, average order value (AOV), and customer growth powered by **Recharts**.
- **Instant Telegram Order Dispatch:** Webhook fires directly to the store manager's Telegram chat the millisecond an order is paid.
- **Printable Thermal Receipts:** High-fidelity printable customer receipts and order packing slips formatted for physical ticket printers.
- **Dynamic Store Configuration:** Manage store branding, contact info, and business hours directly from the UI without touching code.

---

## 🛠️ Technology Stack Breakdown

| Tier                | Technologies                           | Role & Purpose                                                       |
| :------------------ | :------------------------------------- | :------------------------------------------------------------------- |
| **Frontend**        | React 19, Vite, React Router v7        | Blazing-fast Single Page Application routing & rendering             |
| **Styling & UI**    | Tailwind CSS v4, Framer Motion, Lucide | Modern design tokens, editorial micro-interactions, dark/light theme |
| **Data Viz**        | Recharts, Axios, QRCode.react          | Metric dashboards, REST client interceptors, dynamic KHQR display    |
| **Backend API**     | Laravel 11, PHP 8.2+, Eloquent ORM     | Modular RESTful architecture, relational models, migrations          |
| **Security**        | Laravel Sanctum, Google API Client     | Token authentication, password hashing, Google OAuth verification    |
| **Storage & Cloud** | Cloudinary SDK                         | Seamless offloaded media storage and CDN optimization                |
| **Integrations**    | Bakong KHQR, ABA PayWay, Telegram Bot  | Payment gateway processing and automated push alerts                 |

---

## 📸 Sneak Peek & Core Flows

```
[Storefront Browsing] ──► [Product Detail & Cart] ──► [Address & Shipping]
                                                              │
                                                              ▼
[Admin Dashboard & Receipt] ◄── [Telegram Alert] ◄── [Bakong KHQR Scan]
```

---

## 📬 Let's Connect!

I am always interested in discussing full-stack architecture, frontend engineering, and exciting opportunities.

- 🌐 **Portfolio:** [https://jvke-dev.vercel.app/](https://jvke-dev.vercel.app/)
- 🐙 **GitHub:** [@Piseth-007](https://github.com/Piseth-007)
- 📂 **Project Repository:** [FullStack-E-commerce](https://github.com/Piseth-007/FullStack-E-commerce)

---

<div align="center">
  <sub>Crafted with passion, precision, and clean code by <b>Jvke</b>. © 2026</sub>
</div>

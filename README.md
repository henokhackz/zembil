# 🛍️ Zembil – Full-Featured E-commerce Web App

Zembil is a fullstack e-commerce web application built to demonstrate real-world skills in modern web development. It includes everything from authentication and admin dashboards to product management and third-party integrations like Stripe, PayPal, Uploadthing, and Resend.

> ⚡ Built with Next.js, TypeScript, PostgreSQL, Prisma, and Tailwind CSS.

![Zembil Screenshot](/public/images/screen.png)

---

## 📌 Features

- 🔐 Secure Authentication with NextAuth
- 🧑‍💼 Role-based access control (Admin & Customer)
- 🛒 Shopping cart with interactive checkout
- 💳 Payment Integration (Stripe, PayPal, Cash on Delivery)
- 📦 Product & Order Management
- 🌟 Rating & Review System
- 🔍 Search, Filter, Sort, and Pagination
- 🌙 Dark / Light Mode
- 🧑‍💻 Admin Dashboard with Recharts
- 📤 Image Uploads with Uploadthing
- 📧 Email Notification via Resend
- 🧠 Clean and modular codebase

---

## 🧠 Tech Stack

| Category      | Tools / Libraries                                |
| ------------- | ------------------------------------------------ |
| Frontend      | Next.js, TypeScript, Tailwind CSS, React Query   |
| Backend       | Next.js API Routes, Prisma, PostgreSQL           |
| Auth          | NextAuth.js                                      |
| Payments      | Stripe, PayPal                                   |
| File Uploads  | Uploadthing                                      |
| Email         | Resend                                           |
| Charts        | Recharts                                         |
| Deployment    | Vercel                                           |

---

## 📁 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/henokhackz/zembil.git
cd zembil

npm install
# If you face any issues:
npm install --legacy-peer-deps
DATABASE_URL=""
NEXTAUTH_SECRET="your-generated-secret"

PAYPAL_CLIENT_ID=""
PAYPAL_APP_SECRET=""

STRIPE_SECRET_KEY=""
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=""

UPLOADTHING_TOKEN=""
UPLOADTHIUG_SECRET=""
UPLOADTHING_APPID=""

RESEND_API_KEY=""

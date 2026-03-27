# 🕯️ Scented Candle — Full-Stack E-Commerce Platform

A production-ready e-commerce platform for selling scented candles online. Built with Next.js 15, React 19, Clerk Auth, Razorpay payments, and dual database support (Supabase + Firebase).

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![Razorpay](https://img.shields.io/badge/Razorpay-Payments-0C2451)
![Clerk](https://img.shields.io/badge/Clerk-Auth-6C47FF?logo=clerk&logoColor=white)

---

## ✨ Features

- **Complete E-Commerce** — Product catalog, cart, and checkout
- **Payment Processing** — Razorpay payment gateway integration
- **User Authentication** — Secure auth with Clerk
- **Dual Database** — Supabase + Firebase for flexibility
- **Email Notifications** — Nodemailer for order confirmations
- **Product Carousel** — Swiper-based product browsing
- **State Management** — Zustand for lightweight state
- **Smooth Animations** — Framer Motion transitions
- **Responsive Design** — Tailwind CSS mobile-first
- **CI/CD Pipeline** — GitHub Actions for automated deployment

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 15 | React framework |
| React 19 | UI library |
| TypeScript 5.7 | Type-safe development |
| Clerk | Authentication |
| Razorpay | Payment processing |
| Supabase | Primary database |
| Firebase | Secondary database |
| Nodemailer | Email service |
| Zustand | State management |
| Framer Motion | Animations |
| Tailwind CSS | Styling |
| Swiper | Product carousel |

---

## 🚀 Quick Start

```bash
git clone https://github.com/dipk2003/scented-candel.git
cd scented-candel
npm install
npm run dev
```

### Environment Variables

```env
# Clerk Auth
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...

# Supabase
NEXT_PUBLIC_SUPABASE_URL=...
NEXT_PUBLIC_SUPABASE_ANON_KEY=...

# Firebase
NEXT_PUBLIC_FIREBASE_API_KEY=...

# Razorpay
RAZORPAY_KEY_ID=...
RAZORPAY_KEY_SECRET=...

# Email
SMTP_HOST=...
SMTP_USER=...
SMTP_PASS=...
```

---

Made with ❤️ by [Dipanshu Pandey](https://github.com/dipk2003)
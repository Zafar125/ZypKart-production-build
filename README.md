# ZypKart-production-build
ZypKart — A full-scale AI-powered e-commerce platform built with Next.js 14, TailwindCSS, Prisma, PostgreSQL, Stripe/Razorpay, and real-time global product pricing. Includes storefront, seller onboarding, admin panel, AI search, checkout, inventory, and real-time integrations. Production-ready build.


# 🌐 ZypKart — AI-Powered E-Commerce Platform

**Next.js 14 • TailwindCSS • PostgreSQL • Prisma • Stripe/Razorpay • NextAuth • AI Search • Real-Time Pricing**

ZypKart is a full-scale, production-ready AI-powered e-commerce marketplace built to compete with Amazon, Flipkart, Walmart, Etsy, and BestBuy.

It supports **buyers**, **sellers**, **admins**, and **AI-driven experiences** with global real-time prices, product recommendations, secure payments, and high-performance SSR pages.

---

## 🚀 Features

### 🛍️ Storefront

* SSR product pages
* Category pages
* Real-time pricing (Amazon, Flipkart, Walmart, eBay APIs – demo mode)
* Live exchange rates (USD, INR, AED, GBP, EUR)
* Smart search (AI/Lexical/Fuzzy)
* Reviews + ratings

### 🛒 Cart & Checkout

* Server-side cart
* Coupons
* Tax / shipping estimation
* Stripe / Razorpay payments
* Email receipts

### 🏪 Seller Platform

* Seller onboarding + KYC
* Product uploads (UploadThing)
* Inventory management
* Dashboard with sales analytics

### 🔐 Auth & Security

* NextAuth (Email/Google/GitHub)
* Role-based access (user/seller/admin)
* Rate limiting
* API protection

### 🛠️ Admin Suite

* User management
* Seller approvals
* Product moderation
* Analytics dashboard

### 🤖 AI Features

* AI-powered product recommendations
* Smart auto-categorization for sellers
* AI chatbot assistant
* AI vector search

---

## 🧱 Tech Stack

* **Framework:** Next.js 14 (App Router, RSC, SSR)
* **Styling:** TailwindCSS + ShadCN UI
* **Database:** PostgreSQL
* **ORM:** Prisma
* **Auth:** NextAuth
* **Payments:** Stripe or Razorpay
* **Storage:** UploadThing
* **Hosting:** Vercel
* **AI:** OpenAI / embeddings / vector search
* **API Layer:** RESTful Next.js API Routes
* **Deployment:** Vercel + Edge Functions

---

## 📦 Project Structure

```
/app
  /api
  /admin
  /seller
  /product/[id]
  layout.tsx
  page.tsx
/components
/lib
/prisma
/public
```

---

## 🔧 Installation

```bash
git clone https://github.com/YOUR_USERNAME/ZypKart-production-build
cd ZypKart-production-build
npm install
```

---

## ⚙️ Environment Variables

Copy `.env.example` → `.env`

```bash
DATABASE_URL=
NEXTAUTH_SECRET=
STRIPE_SECRET_KEY=
UPLOADTHING_SECRET=
EXCHANGE_RATE_API_KEY=
OPENAI_API_KEY=
```

---

## 🗄️ Database Setup

```bash
npx prisma generate
npx prisma migrate dev
npm run seed
```

---

## 🧪 Run Locally

```bash
npm run dev
```

---

## 🚀 Deploy on Vercel

1. Push repo to GitHub
2. Go to [https://vercel.com](https://vercel.com)
3. Import your repo
4. Add environment variables
5. Deploy with one click

---

## 📜 License

MIT License — free for commercial use.

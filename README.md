# 🚀 Modern SaaS Web App Template

Welcome to the **Converso** – an elegant, full-stack software-as-a-service boilerplate built with performance, scalability, and DX (developer experience) in mind. 🎯

Easily kickstart your own SaaS product with ready-to-use **authentication**, **subscription payments**, **dashboard UI**, and a modular architecture — all powered by **Next.js 14**, **Stripe**, and **Clerk**.

<div align="center">
  <img src="https://img.shields.io/github/stars/elmurodvokhidov/converso?style=for-the-badge" alt="Stars">
  <img src="https://img.shields.io/github/forks/elmurodvokhidov/converso?style=for-the-badge" alt="Forks">
  <img src="https://img.shields.io/github/issues/elmurodvokhidov/converso?style=for-the-badge" alt="Issues">
  <img src="https://img.shields.io/github/license/elmurodvokhidov/converso?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/last-commit/elmurodvokhidov/converso?style=for-the-badge" alt="Last Commit">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge" alt="PRs Welcome">
</div>

---

## 🎯 Features at a Glance

* 🔐 **Clerk Authentication** – Sign in with email, Google, or other OAuth providers
* 💳 **Stripe Payments** – Recurring subscription billing with webhook handling
* 🧠 **AI API Integration** – Easily plug in OpenAI or similar APIs
* 🧑‍💼 **User & Admin Dashboard** – Beautiful and minimal layout with shadcn/ui
* 💌 **Transactional Emails** – Email triggers with Resend or similar service
* 🛠️ **Server Actions & Edge Runtime** – Leverage the latest from Next.js 14
* 🌈 **Dark Mode Ready** – Toggle-friendly theme switch
* 📱 **Fully Responsive** – Built with Tailwind CSS, optimized for mobile
* 📂 **Modular Folder Structure** – Clean and scalable project organization
* 🌍 **SEO & Metadata Optimization** – Ready for production

---

## 🧰 Tech Stack

| Frontend        | Backend / Infra     | APIs & Tools       |
| --------------- | ------------------- | ------------------ |
| Next.js 14 ⚛️   | App Router & Edge ⚡ | Clerk 🔐           |
| TypeScript 🟦   | Server Actions 🧠   | Stripe 💳          |
| Tailwind CSS 🎨 | Webhooks 🔁         | OpenAI / Resend 💬 |
| Shadcn/ui 🧩    | Middleware & RSC 🧪 | Vercel ▲           |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/elmurodvokhidov/converso.git
cd converso
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env.local` file in the root:

```env
CLERK_PUBLISHABLE_KEY=your-clerk-key
CLERK_SECRET_KEY=your-secret-key
STRIPE_SECRET_KEY=your-stripe-key
STRIPE_WEBHOOK_SECRET=your-webhook-secret
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-key
OPENAI_API_KEY=your-openai-key
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

### 4. Run the App

```bash
npm run dev
```

> Don’t forget to set up Stripe webhook forwarding (e.g., with `stripe listen`) for full subscription flow!

---

## 🙏 Special Thanks

A heartfelt thank you to [Adrian Hajdin](https://github.com/adrianhajdin) 🙌
Your clear explanations, elegant code structure, and teaching style made this project not only possible but a joy to learn from.
This version builds upon your vision, with added tweaks and customization for my own development journey. Infinite respect! 💙

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
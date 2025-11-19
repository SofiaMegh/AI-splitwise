# 💸 AI Smart Expense Sharing App

> ⚠️ **Demo Project – Experimental Build**
> This project is a proof-of-concept and experimental implementation of a **Splitwise like app** built with a full-stack modern web architecture. It showcases real-time expense management, AI-driven insights, and smart debt settlement logic designed for individuals and groups.
> It serves as a demo before the final version is customized and deployed for a client.

---

## 🚀 Overview

The App simplifies how groups handle shared expenses. From tracking who paid what to smartly optimizing settlements, the system integrates real-time collaboration with AI insights for smarter financial management.

---

## ✨ Key Features

* **Group & Personal Expenses:** Add, split, and manage expenses individually or across groups.
* **Flexible Splitting Options:** Split equally, by percentage, or custom amounts per participant.
* **Smart Debt Simplification:** AI-powered algorithms minimize redundant transactions.
* **Real-Time Sync:** Built on Convex for instant updates — no manual refreshes required.
* **Secure Authentication:** Powered by Clerk with support for Google/email login.
* **AI Insights (Gemini):** Monthly spending analysis, smart reminders, and anomaly detection.
* **Analytics Dashboard:** Visual overview of balances, settlements, and monthly summaries.
* **Automated Notifications:** CRON jobs via Inngest send reminders and insights.
* **Beautiful UI:** Crafted using Next.js, Tailwind CSS, Shadcn UI, and Lucide icons.
* **Data Validation:** Integrated with React Hook Form and Zod for robust input handling.

---

## 🧠 Tech Stack

| Layer              | Tools & Libraries                             |
| ------------------ | --------------------------------------------- |
| **Frontend**       | React 19, Next.js 15, Tailwind CSS, Shadcn UI |
| **Backend**        | Convex (real-time DB), Prisma ORM             |
| **Auth**           | Clerk                                         |
| **AI Integration** | Gemini AI for analytics & insights            |
| **Scheduling**     | Inngest for CRON jobs and reminders           |
| **Deployment**     | Vercel (CI/CD, environment management)        |

---

## 🔄 User Flow

1. **Sign Up/Login** securely via Clerk.
2. **Create or Join Groups** and add members or contacts.
3. **Add Expenses** with flexible split modes (equal, percentage, exact).
4. **Settle Debts** automatically through circular debt optimization.
5. **View Dashboard** for balance sheets and AI-powered tips.
6. **Receive Reminders** and insights monthly via automated jobs.

---

## 📈 Why I built it?

This project demonstrates **production-level full-stack engineering** for financial applications, blending AI analytics, real-time data sync, and scalable architecture.

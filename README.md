# Vault – Smart Personal Finance Management

**Vault** is a modern full-stack personal finance platform built to help users **analyze spending**, **plan budgets**, and **receive intelligent financial insights** — all through an elegant, secure, and scalable interface.

With support for **automated financial workflows**, **AI-driven reports**, and **transactional emails**, Vault takes personal finance to the next level.

---

## ✨ Key Features

- **Advanced Analytics**  
  Get AI-generated insights into your spending behavior with intelligent categorization and summaries.

- **Smart Receipt Scanner**  
  Upload receipts and let Vault extract and categorize expense data automatically using AI.

- **Budget Planning**  
  Set monthly budgets and track performance with real-time progress and smart recommendations.

- **Multi-Account Support**  
  Manage multiple bank accounts and cards with unified tracking and consolidated reporting.

- **Automated Insights**  
  Automatically receive personalized reports, budget summaries, and spending alerts via email.

- **Transactional Emails (via Resend)**  
  Receive budget reports, account summaries, and spending alerts directly in your inbox using **Resend**.

---

## 🤖 AI & Automation

- AI is used for:
  - **Receipt data extraction**
  - **Spending pattern classification**
  - **Natural language report generation**

- **Inngest** is used for:
  - Recurring transaction processing
  - Monthly financial report generation
  - Trigger-based alerting and budget monitoring

---

## 🛠 Tech Stack

| Category         | Technologies                            |
|------------------|-----------------------------------------|
| **Frontend**      | Next.js 14/15 (App Router), Tailwind CSS, ShadCN UI |
| **Backend**       | Node.js, Express                       |
| **Database**      | MongoDB                                |
| **Auth**          | Clerk                                  |
| **AI Integration**| Custom prompts + OpenAI API (or similar) |
| **Scheduling**    | Inngest                                 |
| **Email**         | Resend                                  |
| **Hosting**       | Vercel                                  |

---

## 📷 Screenshots

**Landing Page**

![Screenshot 2025-04-20 002214](https://github.com/user-attachments/assets/57e168af-cdd4-42b1-bca7-26006f4a3591)

**Dashboard**

![Screenshot 2025-04-20 002338](https://github.com/user-attachments/assets/a5290f04-55ea-42d1-9345-3ea9be815170)

**Add Transaction**

![Screenshot 2025-04-20 002353](https://github.com/user-attachments/assets/165628ee-6710-4e85-9fa9-c43afcb5d170)

**All Transactions**

![Screenshot 2025-04-20 002857](https://github.com/user-attachments/assets/3113ad6a-122d-425a-83e8-cb2185fc079c)



---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/vault
cd vault
npm install
npm run dev

## Make sure to create a `.env` file with following variables -


DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=

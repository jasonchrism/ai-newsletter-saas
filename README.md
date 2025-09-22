# Build a Personalized AI Newsletter SaaS with Next.js & Supabase

<div align="center">
  <h3 align="center">Build a Personalized AI Newsletter SaaS with Next.js, Supabase, OpenAI & Inngest</h3>

## ⚙️ Tech Stack

- **Next.js 15+** – React framework with App Router & server components
- **Supabase** – Hosted Postgres, authentication & real-time subscriptions
- **OpenAI GPT-4** – AI-powered newsletter content generation
- **Inngest** – Durable background jobs for newsletter scheduling
- **TailwindCSS** – Utility-first styling
- **TypeScript** – Static typing and developer tooling
- **EmailJS** – Email delivery service
- **NewsAPI** – News article fetching

---

## ⚡️ Features

- 🎯 **Category Selection**
  Choose from 8 different news categories (Technology, Business, Sports, Entertainment, Science, Health, Politics, Environment).

- 🤖 **AI-Powered Summarization**
  Uses OpenAI GPT-4 to create engaging, personalized newsletter content from recent news articles.

- ⏰ **Scheduled Delivery**
  Automatically sends newsletters at 9 AM based on user-selected frequency (daily, weekly, bi-weekly).

- 🔄 **Durable Workflows**
  Built with Inngest for reliable background processing and automatic retries.

- 👤 **User Management**
  User authentication, preference management, and newsletter activation/deactivation.

- 📱 **Responsive Dashboard**
  Beautiful, mobile-friendly UI with real-time status updates and preference management.

- 💳 **Subscription Billing**
  Stripe integration for premium features and subscription management.

- 📧 **Email Delivery**
  Professional email templates with HTML formatting and tracking.

---

## 👌 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [Supabase CLI](https://supabase.com/docs/guides/cli)
- Supabase project (URL & ANON key)
- OpenAI API key
- Inngest account (signing key)
- NewsAPI key
- EmailJS account (service ID, template ID, public key)
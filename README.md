# 🚀 AI SaaS Content Generator (Next.js + OpenAI + Supabase)

A production-grade AI-powered SaaS platform that generates high-quality content (bios, posts, branding text) using LLMs, with user authentication, usage tracking, and scalable architecture.

> Designed as a real-world SaaS product with focus on performance, scalability, and user experience.

---

## 🌐 Live Demo

https://pallyy.com/?threadcreator=true

---

## 📦 GitHub Repository

👉 https://github.com/Ajendranath/AI-Saas-Developer-Tool

---

## ✨ Features

### 🤖 AI Content Generation

* Generate Twitter bios, LinkedIn summaries, and custom content
* Powered by OpenAI (LLMs) with optimized prompts
* High-quality, context-aware outputs

---

### 🔐 Authentication (Supabase)

* Secure login/signup system
* Session management
* User-specific data isolation

---

### 📊 User Dashboard

* Track generated content history
* Monitor usage and activity
* Personalized experience

---

### ⚡ Performance & Scalability

* Redis-based rate limiting (API protection)
* Serverless architecture (Vercel)
* Optimized API response handling

---

### 🧠 Smart Prompt Engineering

* Dynamic prompt construction
* Context-aware generation
* Output refinement system

---

## 🏗️ Tech Stack

### Frontend

* Next.js (React)
* Tailwind CSS

### Backend

* Node.js (API routes)
* REST APIs

### Database

* Supabase (PostgreSQL)

### AI Integration

* OpenAI API (GPT models)

### DevOps & Tools

* Vercel (Deployment)
* Redis (Rate Limiting & Caching)

---

## 📁 Project Structure

```id="p1"
/app
/components
/lib
  ├── supabaseClient.js
  ├── openai.js
/pages/api
  ├── generate-content.js
  ├── user-usage.js
  ├── save-history.js
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash id="p2"
git clone https://github.com/Ajendranath/AI-Saas-Developer-Tool.git
cd AI-Saas-Developer-Tool
```

---

### 2️⃣ Install dependencies

```bash id="p3"
npm install
```

---

### 3️⃣ Setup environment variables

Create `.env.local`:

```env id="p4"
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
OPENAI_API_KEY=your_openai_key
REDIS_URL=your_redis_url
```

---

### 4️⃣ Run locally

```bash id="p5"
npm run dev
```

App runs at:

```id="p6"
http://localhost:3000
```

---

## 📊 Database Design (Supabase)

### Users

* id
* email

### Generations

* id
* user_id
* input_prompt
* generated_output
* created_at

---

## 🚀 Future Enhancements

* 💳 Stripe subscription (SaaS billing)
* 📈 Advanced analytics dashboard
* 🧠 AI personalization using embeddings
* 🌐 Multi-language content generation
* 📊 Usage quota system

---

## 💡 Why This Project?

This project demonstrates:

* Real-world **AI SaaS product development**
* Full-stack architecture (Next.js + APIs)
* Scalable backend design with rate limiting
* Database modeling with PostgreSQL (Supabase)
* Product thinking and monetization potential

---

## 🧑‍💻 Author

**Ajendra Nath Tripathi**
Final Year CSE Student | Aspiring Software Engineer

---

## ⭐ Support

If you found this project useful:

* ⭐ Star the repo
* 🍴 Fork and improve
* 🛠️ Contribute via PR

---

## 📜 License

MIT License

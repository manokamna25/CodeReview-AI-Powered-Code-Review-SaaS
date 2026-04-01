<div align="center">

# 🚀 CodeMoney 

**Your AI-Powered Code Reviewer & Repository Insights Platform**

[![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)](https://www.prisma.io/)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)

*(Insert Awesome Project GIF/Screenshot Here)*  
`![CodeMoney Demo](https://via.placeholder.com/800x400.png?text=CodeMoney+Demo+GIF)`

</div>

---

## 🌟 What is CodeMoney?

CodeMoney is like having a senior developer reviewing your code 24/7! It connects your GitHub repositories to **Google's Gemini AI** to automatically review your Pull Requests, find bugs, and suggest improvements. Plus, it gives you a beautiful dashboard to track all your coding activity! 

---

## ✨ Features That Make It Awesome

- **🤖 AI Pull Request Reviews:** Tired of waiting for code reviews? Our AI automatically analyzes your PR changes and gives you smart feedback instantly!
- **📊 Activity Dashboard:** See your entire coding life in one place. Track your repositories, commits, PRs, and AI reviews beautifully.
- **🔗 Seamless GitHub Integration:** Just log in with GitHub and you're good to go! Easy peasy.
- **📈 Contribution Visualizer:** A stunning contribution graph (like GitHub's) but supercharged with insights.
- **🔍 Smart Code Search (RAG):** We use Pinecone (a vector database) to "read" your entire codebase so the AI actually understands your project context!
- **💳 Built-in Subscriptions:** Monetization ready and powered by Polar.sh for offering premium tools!

---

## 🛠️ Tech Stack Built for Speed

We built CodeMoney using the best modern tools:

### Everything You See (Frontend)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white)

### Everything Behind the Scenes (Backend)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-000000?style=for-the-badge)

### The Brains & Infrastructure
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![Better Auth](https://img.shields.io/badge/Better_Auth-000000?style=for-the-badge)

---

## 🚀 Let's Get Running!

Follow these simple steps to run CodeMoney on your own machine.

### 📋 What You Need First (Prerequisites)
Make sure you have these ready:
- Node.js 18+ (or Bun!)
- A PostgreSQL Database
- A [Google AI Studio API Key](https://aistudio.google.com/) (It's free!)
- A [Pinecone Account](https://www.pinecone.io/) & Index
- A GitHub OAuth App (for login)

### 💻 Installation

**1. Copy the code to your machine**
```bash
git clone https://github.com/manokamna25/CodeReview-AI-Powered-Code-Review-SaaS.git
cd CodeReview-AI-Powered-Code-Review-SaaS
```

**2. Install all the packages**
```bash
npm install
# or if you like it fast:
bun install
```

**3. Set up your secrets (.env file)**  
Create a new file named `.env` in the root folder and add your secret keys like this:

```env
# 🐘 Database Setup
DATABASE_URL="postgresql://user:password@localhost:5432/codemoney"

# 🔐 Authentication Setup
BETTER_AUTH_SECRET="your_secret_here"
NEXT_PUBLIC_APP_URL="http://localhost:3000"
GITHUB_CLIENT_ID="your_github_client_id"
GITHUB_CLIENT_SECRET="your_github_client_secret"

# 🧠 AI Brain
GOOGLE_GENERATIVE_AI_API_KEY="your_api_key_here"

# 🔍 Code Search Memory
PINECONE_DB_API_KEY="your_pinecone_api_key"

# ⚙️ Background Tasks
INNGEST_EVENT_KEY="your_inngest_key"
INNGEST_SIGNING_KEY="your_inngest_signing_key"

# 💰 Subscriptions
POLAR_ACCESS_TOKEN="your_polar_token"
POLAR_WEBHOOK_SECRET="your_polar_webhook_secret"
```

**4. Setup the database tables**
```bash
npx prisma db push
```

**5. Start the engine! 🏎️**
```bash
npm run dev
```
🎉 **Boom!** Your app is now running at `http://localhost:3000`

---

## 🏗️ How Things Are Organized

Here's a quick map of our code town:

```text
├── app/              # 🏠 Next.js Pages & Routes (What you see)
├── components/       # 🧩 Reusable beautiful UI pieces
├── module/           # 🧠 Core logic (AI, Payment, Github logic)
├── prisma/           # 🗄️ Database structure
├── lib/              # 🧰 Tools and configurations
├── hooks/            # 🎣 React helpers
└── public/           # 🖼️ Images and icons
```

---

## 🤝 Join the Fun! (Contributing)

Community is what makes open-source amazing! Any help is **super appreciated**.

1. **Fork** the project
2. Create your Feature Branch: `git checkout -b feature/CoolNewFeature`
3. Commit your Changes: `git commit -m 'Added cool magic'`
4. Push to the Branch: `git push origin feature/CoolNewFeature`
5. Open a **Pull Request** and let's review it!

---

## 🛡️ License

This project is completely free to use under the **MIT License**. Check out the `LICENSE` file for more details.

---

<p align="center">Made with ❤️ by <strong><a href="https://github.com/manokamna25">manokamna25</a></strong></p>

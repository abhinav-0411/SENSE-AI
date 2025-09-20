# SENSE-AI 🚀  
**AI-Powered Career Coaching & Resume Builder Platform**

SENSE-AI is an intelligent platform designed to democratize career development.  
It helps students and professionals with **resume optimization, interview preparation, skill-gap analysis, and real-time career recommendations** — all powered by AI.  

---

## 🌟 Features
- 📝 **AI Resume Builder** – Generate, optimize, and format professional resumes.  
- 🤖 **Interview Preparation** – Mock interviews, feedback, and personalized questions.  
- 📊 **Skill-Gap Analysis** – Identify missing skills and suggest learning paths.  
- 🔮 **Career Recommendations** – AI-driven suggestions for jobs and roles.  
- 🔐 **Authentication** – Secure login and user sessions with Clerk.  
- ☁️ **Cloud Deployment** – Hosted on Vercel for scalability and speed.  

---

## 🛠️ Tech Stack
- **Frontend:** React 19, Next.js 15, Tailwind CSS, ShadCN UI  
- **Backend:** Next.js API Routes, Gemini AI (Google)  
- **Database:** NeonDB with Prisma ORM  
- **Authentication:** Clerk  
- **Deployment:** Vercel  

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sense-ai.git
cd sense-ai
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables  
Create a `.env.local` file in the root and add:  
```
DATABASE_URL=your_neondb_url
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_api
CLERK_SECRET_KEY=your_clerk_secret
GEMINI_API_KEY=your_gemini_api_key
```

### 4. Run the Development Server
```bash
npm run dev
```
Now open [http://localhost:3000](http://localhost:3000) 🎉

---

## 📂 Project Structure
```
sense-ai/
│── app/               # Next.js App Router
│── components/        # UI Components
│── lib/               # Utilities & Helpers
│── prisma/            # Prisma Schema
│── public/            # Static Assets
│── styles/            # Global Styles
│── package.json
│── README.md
```

---

## 🤝 Contributing
1. Fork the project  
2. Create a new branch (`feature/your-feature`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push to the branch  
5. Open a Pull Request  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 💡 Vision
SENSE-AI’s goal is to make **career growth accessible, affordable, and intelligent** for everyone worldwide.  

# hackindia-spark-7-north-region-arjuna
Hackathon team repository for Arjuna - [hackindia-team:hackindia-spark-7-north-region:arjuna]

# Rights Navigator
An AI-powered platform that helps citizens discover **government schemes they are eligible for** — using simple language, personalization, and voice support.

---

## 🚀 Problem

Millions of Indians are unaware of government schemes they qualify for.

* Information is scattered
* Eligibility criteria is complex
* No personalized guidance

---

## 💡 Solution

This platform acts as a **Rights Navigator**, where users:

* Describe their situation in simple language
* Get AI-powered scheme recommendations
* See required documents & benefits
* Access everything in one place

---

## ✨ Key Features

* 🤖 **AI Chat Assistant**

  * Ask in natural language
  * Get personalized scheme recommendations

* 📊 **Personalized Dashboard**

  * Schemes based on user profile (age, income, state, occupation)

* 🔍 **Smart Discover Page**

  * Search + filter schemes by category

* 🔊 **Text-to-Speech**

  * Listen to scheme details (accessibility feature)

* 📱 **Responsive UI**

  * Works on mobile + desktop

---

## 🧠 How It Works

1. User logs in with phone number
2. Completes profile (age, income, state, etc.)
3. AI processes query + profile
4. Backend filters schemes
5. User receives:

   * Explanation
   * Matching schemes
   * Benefits & details

---

## 🖥️ Frontend

### Tech Stack

* React (Vite)
* Tailwind CSS
* Framer Motion
* Axios
* React Router
* Lucide Icons

### Pages

* Login
* Onboarding
* Dashboard
* Discover Schemes
* Chat Assistant
* Scheme Details

---

## ⚙️ Backend

### Tech Stack

* Node.js
* Express.js
* MongoDB (Atlas)
* Mongoose
* OpenAI API

### API Endpoints

* `/auth` → login
* `/user` → profile management
* `/schemes` → get schemes
* `/schemes/recommend` → personalized schemes
* `/chat` → AI assistant

---

## 🗄️ Database Structure

### User

* name
* phone
* state
* age
* gender
* occupation
* income

### Scheme

* scheme_name
* level (Central / State)
* state
* category
* tags
* eligibility
* documents
* benefits
* steps

---

## 🔗 MongoDB Setup

```env
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/rights-navigator
```

---

## 🌱 Seed Data

```bash
node seed.js
```

---

## ⚙️ Setup Instructions

### 1. Clone Repo

```bash
git clone <your-repo-url>
cd HackIndia
```

### 2. Install Dependencies

Backend:

```bash
cd backend
npm install
```

Frontend:

```bash
cd frontend
npm install
```

---

### 3. Add Environment Variables

Create `.env` in backend:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
OPENAI_API_KEY=your_openai_key
JWT_SECRET=your_secret
```

---

### 4. Run Project

Backend:

```bash
node server.js
```

Frontend:

```bash
npm run dev
```

---

## 🤖 AI Capability

The system:

* Extracts user details from chat
* Matches relevant schemes
* Generates explanation in simple language

Example query:

> "I am a 25 year old farmer from Punjab earning 1.5L — what schemes are for me?"

---

## 🔊 Accessibility

* Text-to-speech support
* Helps users with low literacy
* Supports voice-based understanding

---

## 🚀 Future Improvements

* 🌍 Multi-language support (Hindi, Punjabi)
* 📍 Location-based recommendations
* 📄 Document checklist generator
* 🧠 Improved AI reasoning
* 🎙️ Voice input support

---

## 🏆 Impact

This platform can:

* Reduce awareness gap
* Simplify government processes
* Empower first-generation citizens
* Increase scheme utilization

---

## 🏁 Hackathon Project

Built for **HackIndia 🚀**

---

## 👨‍💻 Contributors

* Ishtpreet Singh
* Harpreet Singh
* Prerna Kumari
* Akashdeep

---

## ⭐ Show Your Support

If you like this project:

⭐ Star this repo
🚀 Share it
💡 Contribute

---

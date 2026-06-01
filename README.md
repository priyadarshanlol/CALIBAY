# CALIBAY
AI-powered resume analyzer and skill gap detector for Indian college students — built for the job-ready generation.
[README.md](https://github.com/user-attachments/files/28450642/README.md)
# 🎯 Calibay

> **AI-powered resume analyzer and skill gap detector for Indian college students.**  
> Know where you stand. Know what to learn. Get hired.

![Status](https://img.shields.io/badge/status-building-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Target](https://img.shields.io/badge/target-Indian%20college%20students-blue)
![Made At](https://img.shields.io/badge/built%20at-Reva%20University-purple)

---

## 🧠 What is Calibay?

Calibay is an AI-first platform that helps Indian college students bridge the gap between their current skills and what recruiters actually want.

Students upload their resume → Calibay parses it using AI → matches it against real job descriptions and market demand → and delivers a personalized **Skill Gap Report** with clear, actionable next steps.

No more guessing why your resume got rejected. No more applying blindly.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 📄 **Resume Parser** | AI reads and structures your resume automatically |
| 🔍 **Skill Gap Analysis** | Compares your skills vs job market demand |
| 📊 **Match Score** | See how well you match for any target role |
| 🗺️ **Learning Roadmap** | Get a personalized step-by-step upskilling plan |
| 🏫 **College Dashboard** | Institutions track student placement readiness (B2B) |
| 💡 **Resource Suggestions** | Curated free/paid resources mapped to your gaps |

---

## 🛠️ Tech Stack

> *(Stack evolving as we build — updated as decisions are finalized)*

**Frontend**
- React.js
- Tailwind CSS

**Backend**
- Python (FastAPI)
- PostgreSQL

**AI / ML**
- Anthropic Claude API — resume parsing & gap analysis
- NLP for resume entity extraction

**Infrastructure**
- Vercel (Frontend)
- Railway / Render (Backend)

---

## 🚀 Getting Started (Local Setup)

```bash
# 1. Clone the repo
git clone https://github.com/YOUR_USERNAME/calibay.git
cd calibay

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install backend dependencies
pip install -r requirements.txt

# 4. Set up environment variables
cp .env.example .env
# Add your API keys to .env

# 5. Run the backend
uvicorn main:app --reload

# 6. Open frontend (in a new terminal)
cd frontend
npm install
npm run dev
```

> Frontend runs on `http://localhost:5173`  
> Backend runs on `http://localhost:8000`

---

## 💰 Revenue Model

Calibay follows a **Freemium + B2B** model targeting the Indian college ecosystem.

```
FREE TIER
└── 3 resume scans/month
└── Basic skill gap report
└── Match score for 1 role

PRO TIER (₹199/month)
└── Unlimited scans
└── Full roadmap with resources
└── Multi-role comparison
└── Resume improvement tips

B2B — INSTITUTIONAL (₹X/year per college)
└── Bulk student onboarding
└── Placement officer dashboard
└── Cohort-level analytics
└── Branded reports
```

---

## 📍 Roadmap

- [x] Concept & brand identity
- [x] Pitch deck (Ignite Milestone 1)
- [ ] Resume parser (MVP)
- [ ] Skill gap engine (Claude API)
- [ ] Match score algorithm
- [ ] Student dashboard UI
- [ ] Landing page
- [ ] Beta launch (Reva University)
- [ ] B2B pilot with 1 college
- [ ] Public launch

---

## 👥 Team

| Name | Role |
|---|---|
| **Priyu** | Founder — Product, Design & AI |

> *Looking for co-founders or collaborators? Reach out.*

---

## 📸 Screenshots

> *(Coming soon — UI in progress)*

---

## 🏆 Competition

Calibay was originally built and pitched for **Ignite — Milestone 1** at Reva University.  
Category: AI/ML Startup · Freemium SaaS

---

## 📬 Contact

- **Instagram / LinkedIn:** *(add your handles)*
- **Email:** *(add your email)*

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

<p align="center">Built with 🔥 by a college student who got tired of rejection emails.</p>

# MwalimuAI

**AI-Powered Teacher Support & Lesson Planner with USSD & Feature Phone Support**

## 🚀 Vision
Empower teachers—especially in rural and low-connectivity areas—with AI-driven lesson planning, quizzes, notifications, and professional development via web, mobile, and feature phones (USSD/SMS).

## 📂 Challenge Categories
- 👩‍🏫 Teacher Support & Professional Development
- 🤖 AI/ML in Education
- 📱 Feature Phone Access & Offline Support

## ❌ Problem
- Many teachers lack updated resources, training, and access to new teaching methods.
- Predominant use of feature phones, so web/mobile apps alone are not sufficient.
- Difficulty staying updated on curriculum, books, and technology.

## ✅ Solution Overview
An AI Lesson Assistant that:
- 📚 Generates engaging, localized lesson plans
- ✏️ Auto-creates quizzes and activities
- 🌍 Adapts to local curriculum & context (Swahili & English)
- 📲 Sends updates about new books, methods, tech
- 📡 Supports USSD and SMS for feature phone users
- 🔑 Empowers teachers, improves lesson quality, scales across schools

## ⚙️ Main Features
- AI-driven lesson and quiz generation
- Class, student, and analytics management
- Admin dashboard (Django)
- USSD/SMS/Push notifications
- Multi-language support (Swahili, English)
- Offline & low-bandwidth support

## 💻 Tech Stack
- **Backend:** Django (Admin, core API), FastAPI/Flask (AI endpoints)
- **Frontend:** React.js (web), USSD (Africa's Talking, etc.)
- **Database:** PostgreSQL, Redis
- **Storage:** AWS S3 (media)
- **DevOps:** Docker, Kubernetes, CI/CD (GitHub Actions), Prometheus, Sentry

## 📱 Feature Phone Support
- USSD entry point: `*123#`
- SMS push for new content, quizzes, updates

## 📑 API Overview
See `/docs` for API specs.

## 🏗️ Project Structure
```
backend/    # Django/FastAPI backend (API, AI, admin)
frontend/   # React web app
ussd/       # USSD/SMS integration
docs/       # Documentation, API specs
infra/      # Docker, deployment, CI/CD
```

## 🗂️ Key APIs
- `/auth/*` — Authentication, OTP, Profile
- `/lessons/*` — Lesson CRUD, AI generation
- `/quizzes/*` — Quiz management
- `/ai/*` — AI text/quiz generation
- `/notifications/*` — SMS/USSD/email notifications
- `/analytics/*` — Reporting & dashboards
- `/classes/*` — Class & student management

## 📝 Contribution Guide
1. Fork & clone the repo
2. Create a feature branch
3. Open a PR with details

## 💥 Impact
- Keeps teachers updated with best practices and resources
- Empowers rural teachers with feature phone support
- Scales to schools with low or no internet

---

**See `/docs/REQUIREMENTS.md` for full specs and `/docs/USSD_FLOW.md` for USSD details.**

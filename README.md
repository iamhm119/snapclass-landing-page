<div align="center">

# 🎓 SnapClass — AI Powered Attendance System

### *Landing Page & Marketing Frontend*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-blueviolet?style=for-the-badge)](https://snapclass-landing-page-ay4u31fke-modihem119-3113s-projects.vercel.app/)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen)]()

</div>

---

## 🚀 Overview

**SnapClass** is an AI-powered attendance management platform that uses **face recognition** and **voice biometrics** to revolutionize classroom attendance tracking. This repository contains the **landing page** — a premium, responsive marketing frontend showcasing the product's features, workflows, and technology stack.

> 🌐 **Landing Page:** [snapclass-landing-page-ay4u31fke-modihem119-3113s-projects.vercel.app](https://snapclass-landing-page-ay4u31fke-modihem119-3113s-projects.vercel.app/)
>
> 🔗 **Live App:** [snapclass-mainurl.streamlit.app](https://snapclass-mainurl.streamlit.app/)

---

## ✨ Features Showcased

| Feature | Description |
|---------|-------------|
| 📸 **AI Face Analysis** | Neural network-based face recognition from class photos |
| 🎙️ **Sequential Voice ID** | Voice biometric matching with stored embeddings |
| 📱 **QR-Driven Roster** | Instant student enrollment via QR codes |
| 🔐 **Secure Authentication** | High-security login for teachers and students |
| 📊 **Actionable Records** | Historical logs, confidence scores, and CSV exports |

---

## 🛠️ Tech Stack

### Landing Page
- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, responsive grid layouts, animations
- **JavaScript** — Intersection Observer scroll reveal animations
- **Google Fonts** — Climate Crisis & Outfit typefaces

### SnapClass Platform (Backend)
- **Streamlit** — Interactive AI dashboard
- **Flask** — Landing page server
- **Supabase** — PostgreSQL database & authentication
- **FaceRecognition + Dlib** — Facial biometric analysis
- **Resemblyzer + Librosa** — Voice embedding & audio AI

---

## 📁 Project Structure

```
snapclass-frontend/
├── index.html              # Static landing page (Vercel entry point)
├── vercel.json             # Vercel deployment configuration
├── app.py                  # Flask dev server (local development)
├── requirements.txt        # Python dependencies (Flask, Gunicorn)
├── templates/
│   └── index.html          # Jinja2 template (Flask version)
├── static/
│   ├── css/
│   │   └── style.css       # Complete stylesheet with responsive design
│   ├── js/
│   │   └── script.js       # Scroll reveal animations
│   ├── img/
│   │   ├── app_logo.png    # Application logo
│   │   ├── logo.png        # Favicon
│   │   └── demo/           # Product screenshots & demo images
│   └── fonts/
│       └── chison.ttf      # Custom font
└── .gitignore
```

---

## 🚀 Deployment

### Vercel (Production)

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the GitHub repository
4. Vercel auto-detects the static site config — click **Deploy**
5. Your site is live! 🎉

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/snapclass-frontend.git
cd snapclass-frontend

# Option 1: Open index.html directly in your browser

# Option 2: Use Flask dev server
pip install -r requirements.txt
python app.py
# Visit http://localhost:5002
```

---

## 📱 Responsive Design

The landing page is fully responsive across all devices:

- **Desktop** (1200px+) — Full layout with floating cards
- **Tablet** (768px–1200px) — Adapted grid layouts
- **Mobile** (< 768px) — Stacked layout with optimized touch targets

---

## 🎨 Design Highlights

- **Dark navbar** with sticky positioning
- **Gradient hero section** with floating product cards
- **Scroll-reveal animations** using Intersection Observer API
- **Purple tech stack section** with glassmorphism cards
- **CTA sections** with high-contrast call-to-action buttons
- **Premium footer** with organized link sections

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with ❤️ for educators everywhere**

*© 2026 SnapClass AI*

</div>

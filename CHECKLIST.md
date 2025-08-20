# ✅ KidLab Development Checklist

A breakdown of tasks into small, independent steps so work can be done in parallel.

---

## 🏗 Project Setup
- [x] Initialize Vue 3 project with Vite
- [x] Configure TypeScript support
- [x] Install TailwindCSS & set up `darkMode: 'class'`
- [x] Install Pinia for state management
- [x] Setup Biome for code quality

---

## 🎨 UI & Styling
- [ ] Create base layout (header, footer, nav)
- [ ] Add TailwindCSS global styles
- [ ] Implement light/dark mode toggle
- [ ] Build responsive navbar
- [ ] Add mobile-first layout adjustments

---

## 🔐 Authentication
- [ ] Setup Supabase project & API keys
- [ ] Install Supabase client in Vue app
- [ ] Create login page (email/password)
- [ ] Create signup page (email/password)
- [ ] Add logout functionality
- [ ] Store auth session in Pinia

---

## 🗄 Database & Features
- [ ] Define `users` table in Supabase
- [ ] Define `experiments` table in Supabase
- [ ] Define `favorites` relation (user ↔ experiment)
- [ ] Add API integration for fetching experiments
- [ ] Add ability to mark/unmark favorite
- [ ] Display user’s favorites page

---

## ⚡ PWA Support
- [ ] Install Vite PWA plugin
- [ ] Configure `manifest.json` (name, icons, theme color)
- [ ] Add service worker for offline caching
- [ ] Test install on Android & iOS

---

## 🚀 Deployment
- [ ] Add `netlify.toml` config
- [ ] Push repo to GitHub
- [ ] Connect GitHub repo to Netlify
- [ ] Verify auto-deploy on push
- [ ] Test live app on mobile browser

---

## 📖 Documentation
- [ ] Write project `README.md`
- [ ] Add `CONTRIBUTING.md`
- [ ] Add LICENSE (MIT)
- [ ] Document Supabase schema (SQL/ERD)
- [ ] Write usage guide for developers

---

## ⚠️ Safety & Disclaimer
- [ ] Add disclaimer to app (in Settings & Readme)
- [ ] Ensure experiments include supervision notes
- [ ] Test user flow for parents & kids

---

## 🎯 Stretch Goals
- [ ] Add social login (Google, GitHub)
- [ ] Add animations for transitions
- [ ] Implement search & filters for experiments
- [ ] Add localization (multi-language support)
- [ ] Add analytics (privacy-friendly)

---

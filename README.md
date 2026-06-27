# ⚡ CppLearn — Master C++ Step by Step

A complete C++ learning platform with courses, live compiler, quizzes, user accounts, admin dashboard, and stunning live background animations.

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Option 1 — Vercel Dashboard (Easiest, No Terminal Needed)

1. **Create a GitHub repository**
   - Go to [github.com](https://github.com) → click **New repository**
   - Name it `cpplearn` (or anything you like)
   - Set it to **Public** or **Private**
   - Click **Create repository**

2. **Upload your files to GitHub**
   - Click **uploading an existing file** on the repo page
   - Drag and drop ALL these files into the uploader:
     ```
     index.html
     404.html
     vercel.json
     package.json
     robots.txt
     sitemap.xml
     .gitignore
     README.md
     ```
   - Click **Commit changes**

3. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com) → Sign up / Log in (use GitHub)
   - Click **Add New → Project**
   - Click **Import** next to your `cpplearn` repository
   - Vercel auto-detects it as a static site
   - Leave all settings as default
   - Click **Deploy**
   - ✅ Your site is live in ~30 seconds!

4. **Your live URL will be:**
   ```
   https://cpplearn.vercel.app
   ```
   (or a custom name Vercel assigns)

---

### Option 2 — Vercel CLI (Terminal)

```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Navigate to your project folder
cd cpplearn-platform

# 3. Login to Vercel
vercel login

# 4. Deploy
vercel

# 5. Follow the prompts:
#    - Set up and deploy? Yes
#    - Which scope? (your account)
#    - Link to existing project? No
#    - Project name: cpplearn
#    - In which directory? ./
#    - Override settings? No

# 6. For production deploy:
vercel --prod
```

---

### Option 3 — Drag & Drop (Fastest)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag your entire project **folder** onto the page
3. Click **Deploy**
4. Done! ✅

---

## 📁 File Structure

```
cpplearn-platform/
├── index.html      ← Main application (all pages, logic, styles)
├── 404.html        ← Custom 404 error page
├── vercel.json     ← Vercel deployment configuration
├── package.json    ← Project metadata
├── robots.txt      ← SEO crawler rules
├── sitemap.xml     ← SEO sitemap
├── .gitignore      ← Git ignore rules
└── README.md       ← This file
```

---

## 🎮 Demo Accounts

| Role  | Email                   | Password  |
|-------|-------------------------|-----------|
| Admin | admin@cpplearn.io       | admin123  |
| User  | alice@example.com       | pass123   |
| User  | bob@example.com         | pass123   |

Or **sign up** to create your own account!

---

## ✨ Features

- **12 Courses** — Beginner, Intermediate, and Advanced C++ tracks
- **60+ Lessons** — Full content for Basics and Control Flow courses
- **Live Compiler** — Write and run C++ in the browser
- **User Auth** — Sign up, log in, 3 role levels (guest / user / admin)
- **Admin Dashboard** — User management, analytics, email logs
- **User Dashboard** — Progress tracking, certificates, profile
- **Welcome Email** — Auto-triggered on signup with preview
- **Library** — Reference materials and cheat sheets
- **Live Animations** — 7-layer animated background (particles, aurora, code tokens, sparkles, etc.)
- **Persistent Data** — All data saved in browser localStorage

---

## 🛠️ Local Development

```bash
# Install serve
npm install

# Run locally
npm start

# Open http://localhost:3000
```

---

## 🌐 Custom Domain on Vercel

1. Go to your Vercel project dashboard
2. Click **Settings → Domains**
3. Enter your domain (e.g. `cpplearn.com`)
4. Update your DNS records as shown by Vercel
5. Done — HTTPS is automatic!

---

## 📝 Notes

- All data is stored in **browser localStorage** — no backend server needed
- The site is a **100% static single-page application**
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Fully responsive on mobile and tablet
- No API keys or environment variables required

---

Made with ❤️ for C++ learners everywhere.

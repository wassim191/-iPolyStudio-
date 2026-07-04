<p align="center">
  <img src="https://res.cloudinary.com/dbjcy5boz/image/upload/v1783159544/cachedImage_isxkwz.png" alt="iPOLY Studio Logo" width="300"/>
</p>

<h1 align="center">iPOLY Studio</h1>

<p align="center">
  Production-deployed portfolio & CMS platform for a Tunisian architectural visualization studio
  <br/>
  <a href="https://www.ipolystudio.com">🌐 Live Website</a>
</p>

---

## 📌 Overview

iPOLY Studio is a full-stack web platform built for a Tunis-based studio specializing in 3D rendering, CGI animation, and architectural visualization for interior and exterior design projects.

The platform consists of two parts:
- **Public showcase website** — portfolio, services, and a multi-step inquiry form
- **Headless CMS admin dashboard** — full content management with granular control over every element

---

## ✨ Features

### Public Website
- 🏗️ Project portfolio with per-project albums and media galleries
- 🎥 3D/CGI showcase with 360° panoramic viewer (Pannellum)
- 📋 Multi-step animated inquiry form with dynamic field management
- 📱 Fully responsive with mobile/desktop-specific content control
- 🔍 Full SEO on every page with Google Search Console integration
- 📊 Vercel Analytics integration

### Admin Dashboard (CMS)
- ✏️ Full content control — text, images, videos, section visibility toggles
- 📁 Project & album management with Cloudinary media storage
- 🛠️ Service pages, process steps, and form field management
- 📬 Inquiry inbox with full submission history
- 📧 Email automation via Mailchimp (13 custom templates) + Zoho mail setup

---

## 🔒 Security Features

- **Row Level Security (RLS)** — Supabase PostgreSQL policies with hardened `is_admin()` using SECURITY DEFINER
- **File upload validation** — attachment type, extension, and size filtering enforced on both frontend and Supabase storage
- **Rate limiting** — max 4 inquiry submissions per IP per hour
- **Honeypot fields** — invisible form fields to detect and reject automated bot submissions
- **Vercel geo-blocking** — regional access control at the edge
- **Input sanitization** — all form fields sanitized before processing
- **Supabase Auth** — secure dashboard authentication

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, TypeScript, Vite, Tailwind CSS, Framer Motion |
| Backend | Supabase (PostgreSQL, Auth, RLS, Storage) |
| Media | Cloudinary, Pannellum (360° viewer) |
| Email | Mailchimp API (serverless function), Zoho Mail |
| Deployment | Vercel |
| Analytics | Vercel Analytics, Google Search Console |

---

## 🎓 Context

Developed as a **final-year academic project (PFA)** at Polytech Monastir in collaboration with Oussama Mansour, under the supervision of Mr. Hatem Jarboua (university) and WD01 (company).

---

> 🔐 *Source code is confidential per client agreement. Live platform available at [ipolystudio.com](https://www.ipolystudio.com)*

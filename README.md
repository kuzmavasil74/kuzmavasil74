<h1 align="center">Hi, I'm Vasyl Kuzma 👋</h1>

<p align="center">
  💻 Full Stack Developer | React • TypeScript • Node.js • Express • MongoDB • PostgreSQL
</p>

<p align="center">
  <a href="https://kuzma-dev-com.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-c70039?style=flat&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://kuzma-dev-com.vercel.app/Vasyl_Kuzma_CV.pdf">
    <img src="https://img.shields.io/badge/CV-PDF-555555?style=flat&logo=adobeacrobatreader&logoColor=white" alt="CV" />
  </a>
  <a href="mailto:kuzmavasil.v@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://t.me/Vasyl_Kuzma">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://www.linkedin.com/in/vasylkuzma/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

### 👨‍💻 About Me

I'm a Full Stack Developer in Prague 🇨🇿. I build complete web applications, from responsive React frontends to REST APIs with authentication, databases and deployment, and I keep them running for real users:

- 🏗 **Part-time developer at [SANJO](https://sanjo.cz)** (construction and cleaning company, Czech Republic): I build their internal tools, BuildTrack and Tool Tracker.
- 💇‍♀️ **Client project in production:** booking platform for the hair salon [TaisiyaStyle](https://taisiiastyle.cz).
- 🎓 **Ph.D. in Physics** before switching to development; GoIT Fullstack course 2023–2024.

**Looking for a full-time developer role** where I can keep shipping real products and grow in a team.

- **Frontend:** React, TypeScript, React Router, Tailwind CSS, CSS Modules, i18n, PWA
- **Backend:** Node.js, Express, REST API design, JWT authentication
- **Databases:** MongoDB (Mongoose), PostgreSQL
- **DevOps & Tools:** Docker Compose, Git, GitHub Actions, ESLint, Vercel, Railway, Render, AWS S3
- **Integrations:** Telegram Bot API, web push, email notifications, PDF/CSV/Excel exports, QR codes

---

### 🔧 Tech Stack & Tools

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwind-css)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel)
![Railway](https://img.shields.io/badge/-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=white)

---

### 🚀 Featured Projects

#### 🏗 [BuildTrack: construction site daily tracker](https://buildtrack-frontend-ten.vercel.app) *(SANJO, in use)*

Daily work tracking for a construction company: who worked on which site, for how many hours, in which crew, and what everyone is owed.

- **Daily records:** one record per site and day, with per-worker start/end times or hours, rates and notes
- **Crews & payroll:** crews with members and hourly rates, monthly payroll in UAH, EUR, PLN, CZK or USD, PDF and CSV export
- **Receipts:** photos stored in AWS S3; QR codes for quick crew check-in
- **PWA in 5 languages:** Ukrainian, English, Polish, Russian, Czech
- **Architecture:** React SPA on Vercel proxies `/api` to an Express API on Railway, so the auth cookie stays first-party; PostgreSQL for users, sites and crews, MongoDB for records and receipts; tests, build and `npm audit` on GitHub Actions

> 🛠 Built with: React 19, Vite, Tailwind CSS 4, react-i18next, Node.js, Express, PostgreSQL, MongoDB, AWS S3, Docker Compose · [API repo](https://github.com/kuzmavasil74/buildtrack) · [frontend repo](https://github.com/kuzmavasil74/buildtrack-frontend)

#### 🧰 Tool Tracker: QR tool inventory *(SANJO, in use, private repository)*

Answers at any moment which tool exists, where it is and who has it, with the full history of every move.

- **QR issue and return:** the storekeeper scans the tool with a phone; every issue, return and handover goes into one event log
- **Bookings** without overlaps, **signed handover PDFs**, **GPS locations on a map**
- **Notifications** in a Telegram group and via web push; loss and "who has what" reports
- **Exports** to CSV, Excel and PDF; roles (admin, storekeeper, viewer); soft delete and daily backups
- **PWA in 3 languages:** Ukrainian, Czech, English

> 🛠 Built with: React, Node.js, Express, Leaflet / OpenStreetMap, Telegram Bot API, Web Push, Railway

#### 💇‍♀️ [TaisiyaStyle: salon booking platform](https://taisiiastyle.cz) *(client project, in production)*

A full-stack booking platform for a professional hair stylist, used by real customers:

- **Online booking:** clients register, log in (JWT) and book services and time slots
- **Telegram bot:** the stylist receives and manages bookings in Telegram
- **Reminders:** a separate worker sends day and hour reminders and asks for a review after the visit
- **Multi-language** interface and responsive design
- **Tested:** unit and integration tests on an in-memory MongoDB replica set

> 🛠 Built with: React, React Router, CSS Modules, Yup, Node.js, Express, MongoDB, JWT, Telegram Bot API, Railway

More projects: **[portfolio](https://kuzma-dev-com.vercel.app/portfolio)**

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kuzmavasil74&show_icons=true&theme=tokyonight&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kuzmavasil74&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

### 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kuzmavasil74&theme=tokyonight&hide_border=true" />
</p>

---

### 🧠 Currently Learning

- **Clean Architecture & Best Practices:** structuring scalable full-stack applications
- **Testing:** wider unit, integration and end-to-end coverage for backend and frontend
- **TypeScript on the Backend:** bringing type safety to my Express APIs

---

### 🎯 Goals for 2026

- 🚀 Land a full-time developer job
- ✅ Keep maintaining and improving the apps that real people use every day
- 🤝 Contribute to open-source projects
- 📚 Keep improving my English & Czech for professional communication

---

> _"Progress over perfection."_ – Me 😊

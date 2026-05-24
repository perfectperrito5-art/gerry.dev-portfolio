<p align="center">
  <a href="" rel="noopener">
    <img width=220px height=220px src="https://i.imgur.com/6wj0hh6.jpg" alt="GERRY.DEV logo">
  </a>
</p>

<h1 align="center">GERRY.DEV — Portfolio Website</h1>

<p align="center">
  <b>// cs student & developer</b> — building systems that turn raw data into real-world decisions.
</p>

<p align="center">
  <a href="#about">About</a> ·
  <a href="#stack">Tech Stack</a> ·
  <a href="#projects">Projects</a> ·
  <a href="#certificates">Certificates</a> ·
  <a href="#contacts">Contacts</a>
</p>

---

## Why this portfolio
I’m <b>Gerry Gerald</b> (CS student & developer). This site is a single-page portfolio designed like a terminal: smooth sections, a neon theme switcher, and a data-driven layout (skills/projects rendered from JavaScript arrays). The mission is simple: <b>building intelligent systems</b> that bridge the gap between raw data and real-world decisions.

---

## 📘 Table of Contents
- [About](#about)
- [Tech Stack](#stack)
- [Projects](#projects)
- [Certificates](#certificates)
- [Current Learning](#current-learning)
- [Features](#features)
- [Contacts & EmailJS](#contacts--emailjs)

---

## 🧠 About <a name="about"></a>
- Web development & backend engineering (including API configuration)
- Database & server administration
- Creative design (code + UX + aesthetics)

I believe learning is a <b>journey</b>, not a destination—every bug is a teacher, every project a milestone.

---

## 🧰 Tech Stack <a name="stack"></a>
Skills are mirrored from the site’s `SKILLS` array:

- HTML5
- CSS3
- JavaScript (ES6+)
- Python
- PHP
- MySQL
- SQL Server
- Creative Design
- MySQL Workbench
- Git & GitHub

---

## 🚀 Projects <a name="projects"></a>
Rendered from the `PROJECTS` array in `portfolio.html`.

### Gerry Portfolio
- **Description:** A modern portfolio showcasing tech skills and a journey in full-stack engineering, creative development, and intelligent systems.
- **Tech/Tags:** HTML, CSS3, JavaScript
- **Links:**
  - GitHub: (set in the page config)
  - Live demo: (optional, set in the page config)

---

## 🏅 Certificates <a name="certificates"></a>
Certificates are controlled by `CERTIFICATES` in `portfolio.html`. The structure is ready—add your real entries when you have them.

---

## 🌱 Current Learning <a name="current-learning"></a>
The “Currently Learning” ticker is powered by the `LEARNING` array:
- Data Structures & Algorithms — CS Core
- System Design Basics — Architecture
- PHP & API Design — Backend
- MySQL Query Optimization — Database
- Git & Github Workflows — Tools
- JavaScript ES6+ — Frontend

---

## ✨ Features <a name="features"></a>
This portfolio is built with engineering-friendly UI patterns:

- **Terminal-style hero** with typewriter bio
- **Neon / Dark / Light theme switcher** (stored in `localStorage`)
- **Scroll-reveal animations** via `IntersectionObserver`
- **Custom cursor** for desktop (disabled on mobile)
- **Responsive navigation** with hamburger menu
- **Data-driven rendering**: skills/projects/certificates generated from JS arrays

---

## 📫 Contacts & EmailJS <a name="contacts--emailjs"></a>
The contact form uses **EmailJS**.

### Setup
1. Create an EmailJS account: https://www.emailjs.com
2. Add an Email Service (e.g., Gmail) → copy **Service ID**
3. Create an Email Template → copy **Template ID**
4. Copy your **Public Key**
5. Paste these values in `portfolio.html`:

```js
const EMAILJS_PUBLIC_KEY  = 'EMAILJS_PUBLIC_KEY_HERE';
const EMAILJS_SERVICE_ID  = 'EMAILJS_SERVICE_ID_HERE';
const EMAILJS_TEMPLATE_ID = 'EMAILJS_TEMPLATE_ID_HERE';
```

### Template variables expected
Your EmailJS template should use:
- `{{from_name}}`
- `{{from_email}}`
- `{{subject}}`
- `{{message}}`

---

## 🛠️ Notes
- `cv.pdf` is referenced by the page (CV download button). Ensure it exists in the repo root if you deploy this site.

---

<p align="center">
  Built with <span>♥</span> & JetBrains Mono — <b>GERRY.DEV</b> © 2026
</p>


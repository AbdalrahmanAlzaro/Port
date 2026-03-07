# Abdalrahman Alzaro — Personal Portfolio

A clean, responsive personal portfolio website for **Abdalrahman Alzaro**, a Full Stack Developer based in Zarqa, Jordan. Built with pure HTML5 and CSS3, featuring a modern bento-grid layout with smooth animations and full mobile responsiveness.

---

## Live Preview

**[View Live Site](https://port-nukohl.vercel.app/index.html)**

> To run locally, serve the project from the root directory via any static file server. The site uses absolute paths (`/Css/`, `/Html/`, `/Assets/`), so it must be served from root — not opened as a plain file.

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero bento-grid with intro, social links, stats, services, and skills |
| About | `Html/about.html` | Bio, contact info, work history, education, skill bars, and graduation project |
| Projects | `Html/projects.html` | Showcase of featured projects with tech stacks and live links |
| Contact | `Html/contact.html` | All contact channels: email, phone, location, LinkedIn, GitHub, and CV download |

---

## Project Structure

```
Port/
├── index.html                  # Home page
├── Html/
│   ├── about.html              # About page
│   ├── projects.html           # Projects page
│   └── contact.html            # Contact page
├── Css/
│   ├── style.css               # Home page styles
│   ├── about.css               # About page styles
│   ├── projects.css            # Projects page styles
│   └── contact.css             # Contact page styles
└── Assets/
    ├── abdalrahman.jpeg        # Profile photo
    └── files/
        └── Abdalrahman Alzaro - Full Stack Developer.pdf  # CV / Resume
```

---

## Tech Stack

The portfolio itself is built with:

- **HTML5** — semantic markup, no frameworks
- **CSS3** — custom bento-grid layout, CSS animations, keyframes
- **[Iconify](https://iconify.design/)** — icon library loaded via CDN (`iconify-icon` web component)
- **Pure CSS hamburger menu** — mobile navigation via checkbox toggle, no JavaScript

---

## Features

- **Bento-grid layout** — modern card-based design on every page
- **Fully responsive** — hamburger menu + stacked layout on mobile
- **Active nav links** — each page highlights its own nav item
- **Skill progress bars** — animated bars showing proficiency levels
- **"Available for work" badge** — green dot indicator on About and Contact pages
- **CV download** — PDF resume directly accessible from About and Contact pages
- **External links** — LinkedIn, GitHub, Instagram, and live project URLs
- **RTL/LTR-aware design** — reflects expertise in bilingual Arabic/English development

---

## Featured Projects

### DisasterAI — Graduation Project · AI
AI-powered disaster detection system using machine learning and computer vision to classify emergency situations from text and images in real time.
- **Text accuracy:** 98.68% | **Image accuracy:** 96.97%
- Stack: `Python` · `FastAPI` · `React` · `PostgreSQL` · `ML / CV`

### Fwaha — E-Commerce
Bilingual (Arabic/English) cosmetics store with Stripe payments, inventory management, and full RTL/LTR UX.
- Live: [fwaha.shop](https://fwaha.shop)
- Stack: `Next.js` · `TypeScript` · `Node.js` · `PostgreSQL` · `Stripe`

### General Authority for Youth — Kuwait · Government
Kuwait's national youth platform serving **100K+ users**. Led frontend development with Redux state management, multiple API integrations, and strict SEO/performance requirements.
- Stack: `Next.js` · `React` · `Redux` · `Axios` · `Laravel API`

### Global Line — Corporate Portfolio
15+ bilingual corporate websites independently built, deployed, and actively maintained in production (1–2 deployments/month).
- Clients include: Palm Gate, Royal Gate, Bronze Bridge, Alamal Layan, and 10+ more
- Stack: `Next.js` · `next-intl` · `Vercel` · `RTL/LTR` · `SEO`

### Knowledge Gateway — CMA · Enterprise Education
Educational platform for Gulf Capital Markets with course browsing and online booking.
- Stack: `Next.js` · `React` · `REST APIs`

### RateMate — Full Stack Capstone
Service review and comparison platform. Users discover and review providers across restaurants, automotive, and home services.
- Stack: `React` · `Tailwind CSS` · `Node.js` · `PostgreSQL` · `JWT`

---

## About Me

**Abdalrahman Alzaro** — Full Stack Developer with **2.5+ years** of experience building bilingual Arabic/English web platforms.

| | |
|---|---|
| **Location** | Zarqa, Jordan — open to remote & on-site worldwide |
| **Education** | B.Sc. Computer Information Systems — The Hashemite University (Feb 2026) |
| **Experience** | Global Line (2024–Now) · Ascot Enterprise Solutions (2022–2024) |
| **Users served** | 100K+ across production platforms |
| **Projects shipped** | 30+ |

### Technical Skills

| Skill | Proficiency |
|-------|------------|
| Tailwind CSS | 92% |
| Next.js | 90% |
| React | 88% |
| Node.js / Express | 85% |
| TypeScript | 82% |
| PostgreSQL | 80% |

---

## Contact

| Channel | Details |
|---------|---------|
| Email | [abdalrahman.h.alzaro@gmail.com](mailto:abdalrahman.h.alzaro@gmail.com) |
| Phone | [+962 78 211 1991](tel:+962782111991) |
| LinkedIn | [abdalrahman-alzaro](https://www.linkedin.com/in/abdalrahman-alzaro/) |
| GitHub | [AbdalrahmanAlzaro](https://github.com/AbdalrahmanAlzaro) |
| Instagram | [abd_h_z](https://www.instagram.com/abd_h_z/) |

---

## Running Locally

Any static server that serves from the project root works. Quick options:

```bash
# Using VS Code Live Server extension — open index.html and click "Go Live"

# Using Python
python -m http.server 8080

# Using Node.js serve package
npx serve .
```

Then open `http://localhost:8080` in your browser.

---

## License

© 2025 Abdalrahman Alzaro. All rights reserved.

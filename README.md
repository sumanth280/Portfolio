<!--
  Colorful, badge-rich, glassy README that works on GitHub (Markdown + safe HTML/SVG only).
  No external JS/CSS. Uses shields.io badges and inline SVG art.
-->

<!-- 🎨 HERO / BANNER (pure SVG, renders on GitHub) -->

<p align="center">
  <svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Portfolio Project Banner">
    <defs>
      <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#7C3AED"/>
        <stop offset="50%" stop-color="#06B6D4"/>
        <stop offset="100%" stop-color="#22C55E"/>
      </linearGradient>
      <filter id="blur">
        <feGaussianBlur in="SourceGraphic" stdDeviation="40" result="b"/>
        <feColorMatrix in="b" type="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7"/>
      </filter>
    </defs>
    <rect width="1200" height="220" fill="#0B1220"/>
    <g filter="url(#blur)" opacity="0.35">
      <circle cx="200" cy="40" r="160" fill="#22C55E"/>
      <circle cx="340" cy="180" r="120" fill="#06B6D4"/>
      <circle cx="1020" cy="60" r="180" fill="#7C3AED"/>
    </g>
    <rect x="90" y="40" rx="24" ry="24" width="1020" height="140" fill="url(#g1)" opacity="0.15" stroke="rgba(255,255,255,0.5)"/>
    <text x="600" y="105" text-anchor="middle" font-size="36" fill="#FFFFFF" font-family="'Poppins', system-ui, -apple-system, Segoe UI, Roboto">Sumanth Nerella — Portfolio Website</text>
    <text x="600" y="140" text-anchor="middle" font-size="18" fill="#C9D1D9" font-family="'Poppins', system-ui">Neumorphism • Glassmorphism • Bootstrap 5 • AOS • GLightbox • Swiper</text>
  </svg>
</p>

<p align="center">
  <a href="https://www.sumanth.online" target="_blank">
    <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-Visit-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://github.com/sumanth280/Portfolio" target="_blank">
    <img alt="GitHub Repo" src="https://img.shields.io/badge/GitHub-Repo-111827?style=for-the-badge&logo=github" />
  </a>
  <a href="#-installation">
    <img alt="Install" src="https://img.shields.io/badge/Install-Guide-22c55e?style=for-the-badge&logo=npm" />
  </a>
  <a href="#-features">
    <img alt="Features" src="https://img.shields.io/badge/Features-Explore-7c3aed?style=for-the-badge" />
  </a>
</p>

<!-- ⭐ GitHub STAR / SOCIAL PROOF (works on GitHub without JS) -->

<p align="center">
  <a href="https://github.com/sumanth280/Portfolio/stargazers" target="_blank">
    <img alt="GitHub Stars" src="https://img.shields.io/github/stars/sumanth280/Portfolio?style=for-the-badge&label=Star%20this%20repo" />
  </a>
  <a href="https://github.com/sumanth280/Portfolio/fork" target="_blank">
    <img alt="GitHub Forks" src="https://img.shields.io/github/forks/sumanth280/Portfolio?style=for-the-badge&label=Fork" />
  </a>
  <a href="https://github.com/sumanth280/Portfolio/issues" target="_blank">
    <img alt="Issues" src="https://img.shields.io/github/issues/sumanth280/Portfolio?style=for-the-badge&label=Issues" />
  </a>
  <a href="https://github.com/sumanth280/Portfolio/commits/main" target="_blank">
    <img alt="Last Commit" src="https://img.shields.io/github/last-commit/sumanth280/Portfolio?style=for-the-badge" />
  </a>
</p>

---

## 🧊 About the Project

A modern, responsive **portfolio website** showcasing academic achievements, certifications, projects, workshops, and conferences. Built with **HTML5, CSS3, JavaScript** using **Bootstrap 5.3+**, **AOS**, **GLightbox**, and **Swiper.js**. Design features **neumorphism** and **glassmorphism**.

> Tip: ⭐ **Star this repo** to keep it handy and get updates.

---

## 🚀 Features

* 📱 **Responsive UI** (Mobile-first with Bootstrap)
* 🎨 **Modern UI/UX** (Neumorphic + Glassmorphic cards)
* 🖼️ **Interactive Gallery** (GLightbox, Swiper)
* 🧭 **Smooth Navigation** (fixed sidebar, in-page anchors)
* 🏆 **Professional Sections** (Awards, Certifications, Workshops, Conferences, Projects)
* 🌐 **Cross-browser Support**
* ⚡ **Performance** (lazy loading, CDN assets, WebP support)

<p align="center">
  <img alt="Tech" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="JS" src="https://img.shields.io/badge/JavaScript-323330?logo=javascript">
  <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white">
  <img alt="AOS" src="https://img.shields.io/badge/AOS-Animations-0ea5e9">
  <img alt="GLightbox" src="https://img.shields.io/badge/GLightbox-Gallery-10b981">
  <img alt="Swiper" src="https://img.shields.io/badge/Swiper.js-Slides-6366f1">
</p>

---

## 🧩 Project Structure

```text
portfolio/
├── index.html                 # Main portfolio page
├── photo.html                 # Photo gallery page
├── inner-page.html            # About/inner page
├── 404.html                   # Error page
├── awards/                    # Awards and certificates section
│   ├── awards.html            # Main awards page
│   ├── national_conference.html
│   ├── international_conference.html
│   ├── workshop.html
│   ├── other.html
│   ├── professional.html
│   ├── simats.html
│   └── ...
├── assets/
│   ├── css/                   # Stylesheets
│   ├── js/                    # JavaScript files
│   ├── img/                   # Images and media
│   └── vendor/                # Third-party libraries
├── robots.txt                 # SEO configuration
├── sitemap.xml                # Site structure
└── CNAME                      # Custom domain configuration
```

---

## 💎 Glass Cards (SVG Previews)

<!-- You can reuse these SVGs as images inside your README sections -->

<p align="center">
  <img src="https://svg-banners.vercel.app/api?type=origin&text1=Sumanth%20Nerella&width=1000&height=180" alt="Glass Banner" />
</p>

<p align="center">
  <a href="https://github.com/sumanth280/Portfolio/stargazers">
    <img alt="Star CTA" src="https://img.shields.io/badge/⭐%20Star%20this%20project-Help%20it%20grow!-rose?style=for-the-badge" />
  </a>
</p>

---

## 🔧 Installation

```bash
# clone
git clone https://github.com/sumanth280/Portfolio.git
cd Portfolio

# open locally
# use VS Code Live Server or open index.html in your browser
```

> Optional: serve via a simple Python server:

```bash
python -m http.server 8080
```

---

## 🧭 Sections

* **Hero**: Intro & profile
* **About**: Personal info
* **Experience**: Work & internships
* **Projects**: Showcase
* **Education**: Academics
* **Awards**: Certificates & achievements
* **Skills**: Bars & badges
* **Interests**: Hobbies
* **Contact**: Reach out

---

## 🛡️ Security

* HTTPS
* CSP-friendly assets
* XSS-safe static site

---

## 📈 SEO

* Meta tags
* Schema.org JSON-LD
* `robots.txt`, `sitemap.xml`

---

## 🌐 Deployment

* **GitHub Pages** / **Netlify**
* Custom domain via **CNAME**
* Auto-HTTPS

---

## 🧪 Browser Support

Chrome 90+, Firefox 88+, Safari 14+, Edge 90+

---

## 🤝 Contributing

Suggestions welcome! Open an issue.

---

## 📜 License

**Personal project — All rights reserved.**

---

## 👨‍💻 Developer

**Sumanth Nerella** — <a href="https://www.sumanth.online" target="_blank">sumanth.online</a>

---








# Soheil Abbasnia — Personal Portfolio Website

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Website: Live](https://img.shields.io/badge/Website-soheilabbasnia.ir-success.svg)](https://soheilabbasnia.ir)
[![Tailwind CSS: 3.x](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Bilingual: EN & FA](https://img.shields.io/badge/Language-English%20%7C%20Persian-blueviolet.svg)](#)

English | [فارسی](README_FA.md)

The source code of the official personal portfolio and resume website of **Soheil Abbasnia** ([soheilabbasnia.ir](https://soheilabbasnia.ir)). Built with modern HTML5, JavaScript, and Tailwind CSS, featuring full bilingual support (English and Persian RTL).

---

## 🌟 Overview

This repository hosts the static front-end assets and templates representing my professional profile, projects, certifications, technical articles, and work experience.

Key highlights:
- **Bilingual & RTL-First**: Seamless language switching between English (`/en/`) and Persian (`/fa/`) with full Right-to-Left typographic care.
- **Dark & Light Mode**: Fluid theme switching with persistent user preference storage.
- **Ultra-Lightweight & Fast**: Zero heavy framework runtime; compiled static assets for instantaneous loading.
- **GitHub Pages Deployment**: Automated continuous deployment to custom domain `soheilabbasnia.ir` with HTTPS.

---

## ✨ Features

- **Profile & Resume**: Direct access to downloadable curriculum vitae (AI & Web Engineering tracks).
- **Project Showcase**: Interactive catalog of open-source libraries, WordPress plugins, AI agents, and web tools.
- **Certificates & Credentials**: Direct verification links for data science, software engineering, and AI certifications.
- **Interactive Contact**: Social media integration, direct email, and instant communication links.

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/soheilabbasnia/soheilabbasnia.ir.git
   cd soheilabbasnia.ir
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start Tailwind CSS watch compiler**:
   ```bash
   npm run watch
   ```

4. **Serve locally** (using Vite or any static HTTP server):
   ```bash
   npm run dev
   ```

---

## 📁 Project Structure

```text
soheilabbasnia.ir/
├── assets/                 # Compiled CSS, images, icons, and JavaScript
│   ├── css/                # Minified Tailwind stylesheets
│   ├── js/                 # Theme switcher and navigation scripts
│   └── images/             # Profile pictures and assets
├── en/                     # English version of the portfolio
│   └── index.html
├── fa/                     # Persian (RTL) version of the portfolio
│   └── index.html
├── src/                    # Tailwind CSS source files
├── index.html              # Root language redirect and landing page
├── CNAME                   # GitHub Pages custom domain configuration
└── package.json            # Development dependencies and build scripts
```

---

## 🤝 Contributing

Suggestions, typo fixes, and constructive feedback are always welcome!
1. Fork the repository.
2. Create your branch (`git checkout -b fix/typo-or-feature`).
3. Commit your changes (`git commit -m 'Fix typo in experience section'`).
4. Push to your branch (`git push origin fix/typo-or-feature`).
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
Feel free to use the layout and structure for your own personal portfolio.

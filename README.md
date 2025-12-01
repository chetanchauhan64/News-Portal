# 📰 News Portal - Next.js 16 Enterprise Edition

![Project Banner](https://via.placeholder.com/1200x400?text=News+Portal+Enterprise+Edition)

A modern, high-performance news application built with **Next.js 16**, **TypeScript**, and **TailwindCSS**. This project features a premium UI, advanced user engagement features, ISR architecture, and professional production-ready coding standards.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-16.0-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.0-38bdf8)](https://tailwindcss.com/)

---

## 🌐 Live Demo

🔗 **Live Project:** https://news-portal-xi-livid.vercel.app/

---

## 🚀 Key Features

This news portal comes with premium, enterprise-level functionalities:

### 🌟 **Modern UI/UX**
- Fully responsive and mobile-first UI  
- Glassmorphism design  
- Smooth animations & micro-interactions  
- Reading progress bar  
- Adjustable font sizes  
- Dark mode ready  

### 🛠️ **Advanced Functional Features**
- Smart search with real-time filtering  
- E-paper digital newsletter (`/newsletter`)  
- User dashboard (`/profile`)  
- Saved articles (`/saved`)  
- Social share for WhatsApp, LinkedIn, and Twitter  
- Reading time estimates  
- LocalStorage persistence  

### ⚡ **Performance + SEO**
- Incremental Static Regeneration (ISR)  
- Dynamic meta tags for SEO  
- JSON-LD structured data  
- Image optimization (WebP/AVIF)  
- Lazy loading for fast performance  
- PWA-ready structure  

---

## 🧰 Tech Stack

| Technology | Usage |
|-----------|--------|
| **Next.js 16** | Full-stack app framework |
| **TypeScript** | Type-safe development |
| **TailwindCSS** | Styling & UI |
| **React Hooks & Context API** | State management |
| **Heroicons** | Icon library |
| **Vitest + fast-check** | Unit & property testing |

---

## 📦 Installation

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/chetanchauhan64/News-Portal.git
cd News-Portal
```
---

### 2️⃣ Install dependencies
```bash
npm install
```
---

### 3️⃣ Environment Setup:Create a .env.local file:
```bash
cp .env.local.example .env.local
```
### Add an API key if needed:
```bash
NEXT_PUBLIC_NEWS_API_KEY=your_api_key
```
---

### 4️⃣ Run Development Server
```bash
npm run dev
```
### Open in browser:
👉 http://localhost:3000

### 📂 Project Structure
```bash

src/
├── app/                    # Next.js App Router
│   ├── article/[id]/       # Dynamic Article Pages
│   ├── category/[slug]/    # Category Listing
│   ├── newsletter/         # E-Paper Digital Page
│   ├── profile/            # User Dashboard
│   ├── saved/              # Saved Articles
│   ├── search/             # Search Results
│   └── layout.tsx          # Main Layout (Navbar/Footer)
│
├── components/             # Reusable Components
│   ├── Header.tsx
│   ├── SideMenu.tsx
│   ├── ArticleCard.tsx
│   ├── Footer.tsx
│   └── VideoPlayer.tsx
│
├── lib/                    # Utilities & helpers
├── services/               # API integrations
└── types/                  # TypeScript interfaces
```
---

### 🧪 Testing
Run all tests:
```bash
npm test
```
Run in watch mode:
```bash
npm run test:watch
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📄 License
Distributed under the **MIT License**. See `LICENSE` for more information.

---

### 💙 Built with Passion

**Made with ❤️ by Chetan Chauhan**

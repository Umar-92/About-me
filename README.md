# About-me
Bio Page — React Static Page
 A personal "About Me" static website built using React + Vite and deployed on GitHub Pages.
 🌐 Live Demo
View it here: http://localhost:5174/
Tech Stack
Frontend Framework: React (with Vite)

Styling: CSS

Deployment: GitHub Pages using gh-pages
 Folder Structure
php
Copy
Edit
bio-page/
├── dist/               # Production build (auto-generated after build)
│   └── assets/         # Compiled JS/CSS/assets
│   └── index.html      # Entry point for deployed site
├── node_modules/       # Dependencies (auto-generated)
├── public/             # Static files (favicon, etc.)
├── src/                # React components and styles
│   ├── components/     # Reusable UI components (e.g., Button, AboutMe)
│   ├── App.jsx         # Main layout component
│   └── main.jsx        # React entry point
├── .gitignore          # Ignore node_modules, dist, etc.
├── index.html          # Root HTML template
├── package.json        # Scripts and dependencies
├── vite.config.js      # Vite configuration
└── README.md           # Project documentation


1. Install Dependencies
bash
Copy
Edit
npm install
2. Run Locally
bash
Copy
Edit
npm run dev


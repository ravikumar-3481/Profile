🚀 AI & Data Science Portfolio | Ravi Kumar Vishwakarma
🔗 Live Demo: https://profileravi.netlify.app
🔗 Live Demo: https://profileravi.vercel.app
Welcome to my professional portfolio!
This project is a data-driven personal website designed to showcase my expertise in Data Science, AI Engineering, and Web Development. It is built with a strong focus on performance, scalability, and clean data architecture.
📁 Project Structure
profileravi/
├── README.md
├── assets/
│   ├── css/
│   │   ├── style1.css
│   │   └── style2.css
│   ├── data/
│   │   ├── activities.json
│   │   ├── certificates.json
│   │   ├── education.json
│   │   ├── experience.json
│   │   ├── other.json
│   │   ├── projects.json
│   │   ├── skills.json
│   │   ├── soft.json
│   │   └── tools.json
│   ├── document/
│   │   └── Ravi Vishwakarma _ Data Scientist Intern _ Resume .pdf
│   ├── img/
│   │   ├── aks.webp
│   │   ├── bg.gif
│   │   ├── cert.webp
│   │   ├── cert1.webp
│   │   ├── cert2.webp
│   │   ├── cert3.webp
│   │   ├── pm.webp
│   │   ├── project1.jpg
│   │   ├── project2.jpg
│   │   ├── project3.jpg
│   │   ├── project4.jpg
│   │   ├── project5.webp
│   │   └── resume.jpg
│   └── js/
│       ├── script.js
│       └── transition.js
├── blog/
│   ├── blog.html
│   └── blog_og/
│       ├── I
│       └── blog.webp
├── index.html
├── og/
│   ├── img.webp
│   └── og.webp
├── resume/
│   └── resume.html
├── robots.txt
└── sitemap.xml

📌 The Problem
Traditional resumes and static portfolios often fail to demonstrate the real-world capabilities of a Data Scientist. This project addresses the following challenges:
 * Information Overload Managing numerous certificates, projects, and skills without cluttering the UI.
 * Maintenance Complexity Updating portfolio content usually requires editing complex HTML files.
 * Performance Issues Displaying high-quality visuals and animations without slowing down mobile load times.
💡 The Solution
To overcome these issues, I implemented a Decoupled Architecture:
 * JSON-Driven Content All dynamic content (projects, skills, experience, education) is stored in modular JSON files. This allows updates without touching UI logic.
 * Asynchronous Rendering JavaScript fetches and renders data dynamically for a smooth and fast user experience.
 * Modern UI/UX A dark-themed, glassmorphic design with animated SVG patterns to reflect a high-tech AI aesthetic.
🛠️ Tech Stack
 * Frontend: HTML5, CSS3 (Advanced Grid & Flexbox), JavaScript (ES6+)
 * Data Storage: JSON (Modular Data Architecture)
 * Animations: CSS Keyframes & SVG Animations
 * Deployment: Netlify with GitHub Actions (CI/CD)
 * SEO: Optimized using robots.txt and sitemap.xml
🚧 Challenges Faced
 * Data Integrity Ensuring all JSON files load correctly and map accurately to UI components.
 * Responsive Design Balancing Orbitron and Poppins typography across devices while maintaining readability.
 * CI/CD Pipeline Configuring GitHub Actions (static.yml) for automatic deployment on every push.

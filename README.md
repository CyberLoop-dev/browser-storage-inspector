<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:047857&height=180&section=header&text=Browser%20Storage%20Inspector&fontSize=34&fontColor=ffffff" width="100%" alt="Browser Storage Inspector banner"></p>
<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=34D399&center=true&vCenter=true&width=620&lines=Inspect+the+storage+for+this+origin;Edit+and+export+without+network+calls" alt="Animated tagline"></p>
<p align="center"><img src="assets/mark.svg" width="100" alt="Storage icon"></p>
<p align="center"><img src="https://img.shields.io/github/license/CyberLoop-dev/browser-storage-inspector?style=flat-square" alt="License"><img src="https://img.shields.io/github/languages/top/CyberLoop-dev/browser-storage-inspector?style=flat-square" alt="Language"><img src="https://img.shields.io/github/stars/CyberLoop-dev/browser-storage-inspector?style=flat-square" alt="Stars"><img src="https://img.shields.io/github/last-commit/CyberLoop-dev/browser-storage-inspector?style=flat-square" alt="Last commit"></p>

## 🧭 Overview
A small local web app for viewing and managing `localStorage` and `sessionStorage` belonging to the origin serving this tool. It never reads storage from other websites and does not transmit stored values.

## ✨ Features
- 🔎 Filter keys and values as you type.
- ✏️ Add, edit, and remove entries in the selected storage area.
- 📦 Export entries to JSON or import a JSON object.
- 📏 See entry counts and approximate value sizes.
- 🔒 All operations happen in the current browser origin.

## 🎬 Demo
No hosted demo is published. Start the server and add a sample key to see it appear in the table.

## 🚀 Quick Start
Requires Node.js 18 or newer.
```bash
npm start
```
Open [http://localhost:4174](http://localhost:4174).

## 🧰 Tech Stack
- Node.js built-in HTTP server
- Browser Storage API, HTML, CSS, and JavaScript
- No runtime dependencies

## 🗂️ Folder Structure
```text
browser-storage-inspector/
├── assets/mark.svg
├── public/{app.js,index.html,style.css}
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🗺️ Roadmap
- [ ] Add optional key-prefix grouping.
- [ ] Add a read-only diff between exported snapshots.
- [ ] Add keyboard navigation for the entries table.

## 🤝 Contributing
Contributions are welcome. Keep storage access limited to the current origin and never add remote telemetry.

## 📄 License
Released under the [MIT License](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:047857,100:111827&height=100&section=footer" width="100%" alt="Footer wave"></p>
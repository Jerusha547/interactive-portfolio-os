# 🖥️ Jerusha.dev — Portfolio OS

A macOS-style interactive portfolio built entirely in **pure HTML, CSS, and Vanilla JavaScript** — zero dependencies, zero frameworks, single file.

🔗 **[Live Demo](https://jerusha547.github.io/portfolio-os)**

---

## ✨ Features

- **Boot sequence** — animated startup screen before the desktop loads
- **Draggable windows** — fully functional drag-and-drop window manager built from raw mouse events and z-index layering
- **Window controls** — close, minimize, and maximize buttons on every window
- **Live clock** — real-time clock and date in the macOS-style menubar
- **Dock with tooltips** — animated dock with hover effects and open-app indicators
- **Interactive terminal** — in-browser terminal with a custom command parser supporting 10+ commands
- **Smooth animations** — boot sequence, window open/close, dock hover effects using CSS keyframes and cubic-bezier curves
- **Multiple app windows** — About Me, Projects, Skills, Achievements, Terminal

---

## 🗂️ Windows / Apps

| Window | Contents |
|---|---|
| 👤 About Me | Bio, contact links, GitHub, LinkedIn, Resume |
| 🗂️ Projects | DevCollab, Online Voting System with live demo links |
| ⚡ Skills | Languages, frameworks, tools, key concepts |
| 🖥️ Terminal | Interactive terminal with custom commands |
| 🏆 Achievements | Problem solving stats, GPA, internship highlights |

---

## 💻 Terminal Commands

Open the terminal from the dock and try:

```
help          → lists all available commands
about         → prints bio summary
skills        → lists technical skills
projects      → lists projects with links
contact       → shows contact info
clear         → clears the terminal
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, keyframes, cubic-bezier) |
| Logic | Vanilla JavaScript ES6+ (DOM API, mouse events) |
| Font | Inter via Google Fonts |
| Hosting | GitHub Pages |

**Zero external dependencies. No React. No libraries. No build tools.**

---

## 🚀 Running Locally

No setup needed:

```bash
git clone https://github.com/Jerusha547/portfolio-os
cd portfolio-os
# open index.html in your browser
```

Or just double-click `index.html`.

---

## 🏗️ Architecture Highlights

- **Window manager** — each window is an absolutely positioned `div` tracked by a shared `zTop` counter; clicking a window increments its `z-index` to bring it to front
- **Drag system** — `mousedown` records offset, `mousemove` repositions the window, `mouseup` clears listeners — no libraries involved
- **Terminal parser** — input is split and matched against a command map; unknown commands return a friendly error
- **Single file deploy** — entire OS is one `index.html`, making it trivially deployable on GitHub Pages

---

## 👩‍💻 Author

**Marumudi Martha Jerusha**  
Full Stack Developer · CSE @ UCE Kakinada  
[LinkedIn](https://www.linkedin.com/in/marumudi-martha-jerusha-2610aa301/) · [GitHub](https://github.com/Jerusha547) · [Email](mailto:marthajerushamarumudi7@gmail.com)

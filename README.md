# 📄 ResumeForge — Smart Resume Builder

> Build professional, print-ready resumes in minutes — directly in your browser. No sign-up, no backend, no nonsense.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-6c63ff?style=for-the-badge&logo=github)](https://minajuddin0510.github.io/Resume-builder)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-ef4444?style=for-the-badge&logo=html5)]()

---

## ✨ Features

- **7 Professional Templates** — Classic · Minimal · Executive · Sidebar · Tech · Elegant · Sharp
- **Live Preview** — See changes instantly as you type, on a true A4 canvas
- **PDF Download** — Print-ready, browser-native PDF export (no third-party library)
- **Auto-Save** — All data persisted to `localStorage`; pick up where you left off
- **Skills Tag Input** — Add skills by pressing Enter or comma; remove with a click
- **Section Reordering** — Drag and drop to arrange sections in any order
- **Accent Color Picker** — Personalize supported templates with 6 accent colors
- **Profile Photo** — Optional photo upload (cropped circular in preview)
- **Rich Education Fields** — GPA, honors, coursework chips, thesis title
- **Completion Progress Bar** — Tracks how filled-in your resume is
- **Fully Responsive** — Mobile-friendly with Edit / Preview tab switcher
- **Zero Dependencies** — Pure HTML, CSS, and vanilla JavaScript; no frameworks, no npm

---

## 🖥️ Screenshots

> *(Add screenshots of your templates here once deployed)*

| Classic | Executive | Sidebar |
|---------|-----------|---------|
| ![Classic]() | ![Executive]() | ![Sidebar]() |

---

## 🚀 Getting Started

### Option 1 — Open Directly

Just open `index.html` in any modern browser. No build step, no server required.

```bash
git clone https://github.com/minajuddin0510/Resume-builder.git
cd Resume-builder
open index.html   # macOS
# or
start index.html  # Windows
```

### Option 2 — GitHub Pages

1. Go to your repo → **Settings → Pages**
2. Set source to `main` branch, `/ (root)`
3. Your resume builder will be live at:
   `https://minajuddin0510.github.io/Resume-builder`

---

## 🗂️ Project Structure

```
Resume-builder/
└── index.html      # The entire app — self-contained single file
```

Everything lives in one file: styles, markup, and JavaScript — making it trivially easy to host, share, or embed.

---

## 📋 Templates

| Template | Style | Best For |
|----------|-------|----------|
| **Classic** | Georgia serif · ATS-friendly | Traditional roles, finance, law |
| **Minimal** | Libre Baskerville · Ultra clean | Design, writing, academic |
| **Executive** | Inter · Dark navy header | Senior roles, management |
| **Sidebar** | Poppins · Two-column colored bar | Creative, tech, startups |
| **Tech** | Courier · Dark code aesthetic | Software engineers, DevOps |
| **Elegant** | Poppins Light · Centered, airy | Fashion, arts, luxury brands |
| **Sharp** | Inter Bold · Numbered sections | Product managers, analysts |

---

## 🛠️ Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts (Poppins · Inter · Libre Baskerville) |
| Storage | `localStorage` (browser-native) |
| PDF Export | `window.print()` with `@media print` styles |

---

## 🔧 Customization

All design tokens are CSS custom properties at the top of the `<style>` block — easy to retheme:

```css
:root {
  --accent:   #6c63ff;   /* Primary brand color */
  --bg-dark:  #0d0f1a;   /* App background */
  --bg-panel: #161926;   /* Panel background */
  --text-1:   #e8eaf2;   /* Primary text */
}
```

To add a new template, define a `.t-yourname` CSS class block and add a render function following the existing pattern in the JS section.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Minaj Uddin**
- GitHub: [@minajuddin0510](https://github.com/minajuddin0510)

---

<p align="center">Made with ❤️ — because your resume deserves to look as good as your work.</p>

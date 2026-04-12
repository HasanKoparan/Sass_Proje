# 🎨 Sass_Proje — GitHub Profile UI Clone

A pixel-perfect clone of the GitHub profile page interface, built with HTML5 and SCSS (Sass). Focuses on modular stylesheet architecture, custom SVG icon system, and responsive design — no JavaScript required.

🔗 **[Live Demo](https://hasankoparan.github.io/Sass_Proje)**

-----

## ✨ Features

- 🖥️ GitHub profile page UI clone
- 🎨 Modular SCSS architecture with partials
- 🔷 Custom inline SVG icon system
- ✍️ Google Fonts — Maven Pro
- 🖱️ Hover effects on interactive elements
- 📱 Responsive layout
- 🧹 CSS normalization and reset
<img width="896" height="517" alt="Ekran Resmi 2026-04-12 13 27 29" src="https://github.com/user-attachments/assets/9b738bbd-03fe-4edd-a7c9-9d498754d2eb" />

-----

## 🛠️ Built With

- **HTML5** — Semantic structure
- **SCSS (Sass)** — Variables, partials, nesting
- **Google Fonts** — Maven Pro
- **SVG** — Custom icon system

-----

## 🧠 SCSS Concepts Used

- Variables (`_variables.scss`)
- Normalize & reset (`_normalize.scss`, `_formalize.scss`)
- Component-based partials (`_header.scss`, `_content.scss`)
- Sass `@import` / `@use` structure
- Nesting and BEM-style selectors
- Source maps (`main.css.map`)

-----

## 📁 Project Structure

```
Sass_Proje/
├── index.html          # Main page markup
├── main.scss           # Entry point — imports all partials
├── main.css            # Compiled output
├── main.css.map        # Source map for debugging
├── _variables.scss     # Global variables
├── _normalize.scss     # CSS normalization
├── _formalize.scss     # Form element resets
├── _header.scss        # Header styles
└── _content.scss       # Main content styles
```

-----

## 🚀 Getting Started

```bash
git clone https://github.com/HasanKoparan/Sass_Proje.git
cd Sass_Proje

# Install Sass
npm install -g sass

# Watch and compile
sass --watch main.scss:main.css
```

Then open `index.html` with Live Server in VS Code.

-----

## 👨‍💻 Author

**Hasan Koparan**

- GitHub: [@HasanKoparan](https://github.com/HasanKoparan)
- LinkedIn: [linkedin.com/in/hasankoparan](https://linkedin.com/in/hasankoparan)

-----

> Built as part of a fullstack development program — practicing real-world UI cloning with modular SCSS architecture. 💪

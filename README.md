# 🌐 Harini's Portfolio — [Harini200434.github.io](https://Harini200434.github.io)

Welcome to the source code of my personal developer portfolio hosted using **GitHub Pages**. This project showcases my skills, projects, and contact information in a clean and responsive design.

---

## 📁 Project Structure

```
📦 root
├── index.html             # Main landing page
├── /assets                # Folder for images, icons, and fonts
│   └── images/
├── /css                   # Styling files
│   └── style.css
├── /js                    # JavaScript for interactivity
│   └── script.js
├── README.md              # Project documentation
└── .gitignore             # Files to ignore in Git
```

---

## 🔍 Code Explanation

### `index.html`
- This is the **entry point** of the portfolio.
- Written in HTML5 with semantic tags for SEO and accessibility.
- Sections usually include:
  - `#about`
  - `#skills`
  - `#projects`
  - `#contact`

```html
<nav>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
```

### `style.css`
- Handles all **styling and responsiveness**.
- Uses media queries for mobile-friendly layout.

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  margin: 0;
}

@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }
}
```

### `script.js`
- Adds **interactivity** like menu toggling or animations.

```js
document.querySelector('.menu-btn').addEventListener('click', () => {
  document.querySelector('.nav-links').classList.toggle('active');
});
```

---

## 💡 Key Features

- 📱 Responsive design for mobile and desktop
- 💼 Project showcase with live links and GitHub repos
- 📫 Contact form or mail link
- 🌙 Dark/light theme toggle (optional)

---

## 🌿 Git & GitHub Concepts Used

### ✅ Git Version Control

- Initialized local Git repo:
```bash
git init
```

- Staged and committed files:
```bash
git add .
git commit -m "Initial commit"
```

- Checked repo status and log:
```bash
git status
git log
```

### 🚀 GitHub Pages Deployment

1. Set remote:
```bash
git remote add origin https://github.com/Harini200434/Harini200434.github.io.git
```

2. Push code to GitHub:
```bash
git push -u origin main
```

3. GitHub auto-publishes from `main` branch because the repo is named `Harini200434.github.io`.

### 🔁 Branching & Collaboration (if used)

```bash
git checkout -b feature/about-section
# After changes
git add .
git commit -m "Added About section"
git checkout main
git merge feature/about-section
```

---

## 📦 Run Locally

```bash
git clone https://github.com/Harini200434/Harini200434.github.io.git
cd Harini200434.github.io
# Open index.html in your browser
```

---

## 📬 Contact

Reach out via the contact form on the website or email mentioned there.

---

## 📝 License

This project is open-source under the MIT License.

# 🖥️ Muhammad Ehsan — Terminal CV & Portfolio

> **A fully interactive, terminal‑style CV website** that presents your professional journey, skills, projects, and certifications in a unique, hacker‑inspired interface. Built for IT support, network, and cybersecurity roles.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Made with ❤️](https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/ehsan42315)
[![Deploy to GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-brightgreen)](https://ehsan42315.github.io/terminal-cv)

---

## ✨ Features

- **Fully interactive terminal** – type commands like `whoami`, `ls ./projects/`, `cat ~/experience` to explore the CV.
- **Complete CV data** – all sections from the original CV are included: education, certifications, detailed work experience, languages, achievements, and more.
- **Live GitHub integration** – fetches real repository stats (stars, forks, last updated) from your public repos.
- **Rich visual effects** – Matrix‑style rain animation, blinking cursor, glowing green accents, and subtle hover animations.
- **Mobile‑friendly** – adapts to any screen size, perfect for viewing on phones and tablets.
- **Keyboard shortcuts** – `⌘+K` / `Ctrl+K` to reload, `⌘+R` / `Ctrl+R` to refresh data.
- **Static fallback content** – works even without a GitHub API connection, using pre‑defined skills and project descriptions.

---

## 📸 Preview

![Terminal CV Preview](https://via.placeholder.com/800x400?text=Terminal+CV+Demo)

> *(Replace the placeholder with an actual screenshot after deployment.)*

---

## 📂 Project Structure

```
.
├── index.html          # Main terminal CV (single-file HTML)
└── README.md           # This file
```

Everything is contained in a single HTML file — no external dependencies, no build tools.

---

## 🚀 Getting Started

### 1. Clone or download

```bash
git clone https://github.com/ehsan42315/terminal-cv.git
cd terminal-cv
```

### 2. Customize for your own data

Open `index.html` and update the following sections:

- **GitHub username** – search for `GITHUB_USERNAME` and replace `'ehsan42315'` with yours.
- **Repository names** – in the `REPO_NAMES` array, list the repos you want to showcase.
- **Fallback descriptions** – in `FALLBACK_DESCS`, edit the descriptions to match your projects.
- **Static skills** – in `STATIC_SKILLS`, adjust the skill names and proficiency levels (1–5).
- **Personal details** – update your name, phone, email, LinkedIn, GitHub, and the text in the `cat ~/.profile` and other sections.

### 3. Preview locally

Simply open `index.html` in any modern browser. It works offline except for GitHub API calls (which will fall back to static content if needed).

### 4. Deploy to GitHub Pages

- Push the repository to GitHub.
- Go to **Settings → Pages**.
- Select the `main` branch and `/ (root)` folder.
- Click **Save** — your site will be live at `https://YOUR_USERNAME.github.io/terminal-cv/`.

---

## 🛠️ Customisation Tips

### Changing the colour scheme

Edit the CSS variables inside the `:root` block:

```css
--bg: #0a0e0f;
--green: #00ff88;
--blue: #4dc9f6;
/* ... etc */
```

### Adding new terminal commands

You can extend the interface by adding new `cat` or `ls` commands. Look at how existing commands are structured in the HTML (e.g., the `cat ~/education` block) and replicate the pattern.

### Changing the Matrix rain effect

Adjust the opacity, speed, or character set inside the `initMatrix()` function in the JavaScript.

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

---

## 🙏 Acknowledgements

- Inspired by the classic terminal aesthetic and hacker culture.
- Built with pure HTML, CSS, and JavaScript — no frameworks.
- GitHub API used to fetch live repository data.

---

## 📬 Contact

- **Name:** Muhammad Ehsan  
- **Email:** muhammad-ehsan234913@gmail.com  
- **LinkedIn:** [linkedin.com/in/muhammad-ehsan-a8610a304/](https://www.linkedin.com/in/muhammad-ehsan-a8610a304/)  
- **GitHub:** [github.com/ehsan42315](https://github.com/ehsan42315)

---

## 🖤 Final Words

> *"I don't just fix problems — I solve them before they happen. 8 years of crisis management taught me that calm is a weapon, and persistence is a tool. With Allah's guidance, I turn challenges into opportunities."*

---

**If you find this useful, give it a ⭐ and share it with others!**

---

### How to Contribute

1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

All contributions are welcome!

---

Made with ❤️ by Muhammad Ehsan — self‑forged IT professional.

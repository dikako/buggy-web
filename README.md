# 🐞 Buggy Web App Demo

This is a **deliberately buggy login page** built with HTML, CSS, and JavaScript to help QA engineers practice writing real-world bug reports. It includes logic errors, UI issues, and broken flows for demo and educational purposes.

---

## 🚀 Live Demo

🌐 [View on GitHub Pages](https://dikako.github.io/buggy-web/)

---

## 📋 Objectives

- Train QA engineers in identifying and reporting bugs
- Demonstrate common frontend issues in a clean UI
- Practice writing structured bug reports

---

## 🐛 Intentional Bugs to Find

| Type | Description |
|------|-------------|
| 🧠 Logic Bug | Login form only throws error if **both** fields are empty (should be either) |
| 🔗 Broken Link | Redirects to `/dashboard` which does not exist |
| 🤷 UX Issue | Error message `"Something went wrong!"` is vague |
| 🔒 Security | No password validation or encryption |
| 🧑‍🦯 Accessibility | No `aria` attributes or `label for` references |
| 🧼 Input | No HTML5 validation used (e.g., `required`) |
| 🎨 Styling | Button always full-width (no state variation) |

---

## 🛠️ Local Setup

```bash
git clone https://github.com/dikako/buggy-web.git
cd buggy-web
open index.html  # or double-click the file in Explorer/Finder

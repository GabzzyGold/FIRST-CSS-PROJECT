# 🛒 Joktolak Mini Supermarket: CSS Final Project

A responsive, multi-page website built with **semantic HTML5** and **modern CSS**. It features a sticky header and footer, an animated welcome banner, a CSS Grid menu table, a styled contact form, and automatic **dark mode**.

> 🎓 **This is my first CSS project.** I built it to practise everything I have learned so far: layout, typography, colour systems, responsive design and accessibility. It is not perfect, but it taught me a lot.

---

## 📸 Preview

<!-- Add a screenshot of your site here, for example: -->
<!-- ![Home page preview](IMAGES/preview.png) -->

---

## ✨ Features

- **4 linked pages**: Home (menu), Hours, Contact and About
- **Sticky header and navigation** that stays visible while scrolling
- **Sticky footer** with an auto-updating copyright year (JavaScript)
- **Animated "Welcome" banner** on the hero image using `@keyframes`
- **CSS Grid menu table** built with `grid-template-areas`, with row-spanning cells
- **Styled contact form** with labels, placeholders and required-field validation
- **Automatic dark mode** via `prefers-color-scheme`
- **Responsive design** with a fluid font size (`clamp()`), a flexible layout and a media query for wider screens
- **Smooth scrolling** for in-page links such as "Back To Top"
- **Accessibility touches**: semantic tags, `alt` text, `lang`, table captions and scopes, and screen-reader-only text

---

## 🧠 What I Practised

| Concept | Where it is used |
| --- | --- |
| CSS reset | `*, *::before, *::after` with `box-sizing: border-box` |
| CSS custom properties (variables) | Colours, fonts, borders and spacing in `:root` |
| Dark mode | `@media (prefers-color-scheme: dark)` overrides the variables |
| Flexbox | Navigation bar (`display: flex`, `justify-content: space-evenly`) |
| CSS Grid | Menu table (`grid-template-areas`) |
| `display: contents` | Lets table rows take part in the grid |
| Animations | `@keyframes showwelcome` on the hero heading |
| Sticky positioning | Header and footer |
| Pseudo-elements | 🌮 emojis added to the heading with `::before` and `::after` |
| Responsive units | `clamp()`, `vh`, `%` and `rem` |
| Google Fonts | *Be Vietnam Pro* and *Oswald* |
| BEM-style naming | Classes such as `.header__nav` and `.menu__item` |
| Semantic HTML | `header`, `nav`, `main`, `article`, `aside`, `figure`, `address`, `details` and more |
| Forms | `fieldset`, `legend`, `label`, `required` and input types |

---

## 📁 Project Structure

```
CSS FINAL PROJECT/
├── CSS/
│   └── style.css        # All site styles
├── FAVICON/             # Site icons (.ico)
├── HTML/
│   ├── index.html       # Home page with the menu table
│   ├── hours.html       # Opening hours
│   ├── contact.html     # Address and contact form
│   └── about.html       # About page with a trivia section
├── IMAGES/              # Store and hero images
└── README.md
```

---

## 🚀 Getting Started

No build tools or installs are needed.

1. **Clone or download** this repository:
   ```bash
   git clone <your-repo-url>
   ```
2. **Open** `HTML/index.html` in any modern browser.
   - Optional: use the **Live Server** extension in VS Code for auto-reload.
3. Use the navigation bar to move between pages.

> 💡 To test dark mode, switch your operating system or browser to dark theme.

---

## 🛠️ Built With

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties, Animations, Media Queries)
- A little vanilla JavaScript (dynamic copyright year)
- [Google Fonts](https://fonts.google.com/)

---

## 🔮 Future Improvements

- [ ] Replace the placeholder taco-shop content (menu, address, about text) with real Joktolak products and details
- [ ] Add a mobile hamburger menu
- [ ] Add a product gallery using CSS Grid
- [ ] Connect the contact form to a real backend or form service
- [ ] Add more media queries for tablets and small phones
- [ ] Deploy with GitHub Pages

---

## 📚 What I Learned

- How to organise styles with variables, sections and consistent class names
- How Grid and Flexbox solve different layout problems
- How to support light and dark themes without extra HTML
- How small details (focus states, alt text, labels) make a site more usable
- How to structure a multi-page website with shared styles

---

## 👤 Author

**Gabzzy**
First CSS project, October 2026

- GitHub: [@your-username](https://github.com/your-username)

---

## 📄 License

This project is for learning purposes. Feel free to explore it and use it as inspiration.
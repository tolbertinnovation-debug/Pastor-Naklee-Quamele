# Pastor Naklee Quamele — Official Website

A modern, professional, responsive website for Pastor Naklee Quamele's ministry —
built as a fast, dependency-free static site that can be hosted anywhere (GitHub
Pages, Netlify, Vercel, or any web server).

## ✨ Features

- **Modern, polished design** — refined navy & gold palette, serif/sans type pairing
  (Fraunces + Inter), generous spacing, and tasteful motion.
- **Fully responsive** — looks great from mobile to widescreen, with a mobile nav drawer.
- **Sections** — Hero, About, Ministries, Sermons, Events, Contact, and Footer.
- **Accessible** — skip link, semantic landmarks, keyboard-friendly nav, `aria` labels,
  and `prefers-reduced-motion` support.
- **Performance-minded** — no frameworks, no build step. Just HTML, CSS, and a little JS.
- **Subtle interactions** — sticky header, scroll-reveal animations, and a demo contact form.

## 📁 Project structure

```
.
├── index.html    # Page markup and content
├── styles.css    # Design system + all styling
├── script.js     # Nav, scroll reveal, sticky header, form feedback
└── README.md      # This file
```

## 🚀 Running locally

It's a static site — just open `index.html` in your browser. To serve it locally
(recommended so fonts/relative paths behave like production):

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🌐 Deploying with GitHub Pages

1. Push to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** to your branch (e.g. `main`) and the root folder.
4. Save — your site publishes at `https://<user>.github.io/<repo>/`.

## ✏️ Customizing

- **Text & content:** edit `index.html` (sermon titles, event dates, contact details).
- **Colors & spacing:** adjust the CSS variables at the top of `styles.css` (`:root`).
- **Photo:** replace the `.about-photo` placeholder block with an `<img>` of the pastor.
- **Contact form:** currently shows a front-end confirmation only. To receive real
  submissions, connect it to a service like Formspree, Netlify Forms, or your own
  endpoint by adding an `action`/`method` to the `<form>` in `index.html`.

---

Made with care for the community. _"For I know the plans I have for you." — Jeremiah 29:11_

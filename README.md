# Late Night Thoughts 🌙

> *"Words kept close, left softly by the window."*

A minimalist, editorial digital poetry journal and literary portfolio website. Designed with clean serif typography, calming pastel palettes, and a tranquil atmosphere for quiet evening reading.

---

## 📖 Table of Contents

- [Overview](#overview)
- [Website Structure](#website-structure)
- [Design & Typography](#design--typography)
- [Features](#features)
- [File Tree](#file-tree)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [License](#license)

---

## 🕯️ Overview

**Late Night Thoughts** is a static multi-page website built to showcase original poems, reflective essays, and late-night musings. The design prioritizes readability, generous whitespace, and responsive layouts that gracefully adapt from desktop screens to mobile phones.

---

## 🗂️ Website Structure

The site consists of the following core pages:

1. **`index.html` (Homepage)**
   - **Hero Section:** Side-by-side title, call to action, and interactive image carousel with hover-reveal navigation arrows and dot indicators.
   - **Poems Archive Preview:** Clean 2-column table list of recent works with dates and links.
   - **About Teaser:** Side-by-side author excerpt and warm reading photo.
   - **Photo Banner:** Responsive 4-image collage strip (rain, roses, cobblestones, piano keys).
   - **Letters (Newsletter):** Inline subscription form for poem alerts.
   - **Quiet Notes:** Contact form for readers to send heartfelt thoughts.
   - **Editorial Footer:** Navigation links, site quote, dynamic copyright year, and back-to-top interaction.

2. **Poem Pages**
   - **`doWeEver.html`:** The opening featured poem, paired with a moody night sky/galaxy banner.
   - **`trustTheFearToFall.html`:** Featuring a warm sepia/golden-toned landscape banner and sky-blue accents.
   - **`aHeartForAHeart.html`:** A winter-themed reflection paired with a frosty twilight aesthetic and custom dividers.

3. **`about.html` (About Me)**
   - Long-form author reflections on solitude, warmth, and the reasons for writing in the quiet hours.
   - Alternating text and photography layout with calls to action.

4. **`contact.html` (Contact / Quiet Notes)**
   - A dedicated slow-correspondence mailbox page.
   - Direct email inquiries, reply schedule information, and a clean contact form.

5. **`archive.html` (Archive)**
   - Complete index of all poems matching the 2-column editorial table layout from the homepage.

---

## 🎨 Design & Typography

- **Headings & Verse:** [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) (Serif)
- **Body & UI Elements:** [Inter](https://fonts.google.com/specimen/Inter) (Sans-Serif)
- **Color Palette:**
  - Sky Blue: `#9dc7e6`
  - Sage / Linen Mist: `#f2f5f3` / `#eee9e0`
  - Page Backgrounds: `#ffffff`
  - Text & Accents: `#111417` (Charcoal) and `#5e6b77` (Muted Slate)

---

## ✨ Features

- **No Framework Dependencies:** Built with pure **HTML5**, **CSS3**, and minimal **vanilla JavaScript**.
- **Interactive Carousel:** Previous/next arrows hidden by default, smoothly appearing on cursor hover, alongside functional pagination dots.
- **Fully Responsive:** Uses CSS Flexbox and CSS Grid breakpoints to ensure fluid scaling across desktop, tablet, and mobile browsers.
- **Unified Navigation:** Consistent top navigation bar and editorial footer across all pages with automated copyright year updates (`new Date().getFullYear()`).

---

## 📂 File Tree

```text
late-night-thoughts/
│
├── index.html              # Main landing page
├── about.html              # Extended author & backstory page
├── contact.html            # Dedicated correspondence / contact page
├── archive.html            # Complete index of published poems
│
├── doWeEver.html           # Poem: "Do we ever"
├── trustTheFearToFall.html # Poem: "Trust the Fear to Fall"
├── aHeartForAHeart.html    # Poem: "A heart for a heart — but you took two"
│
├── mystyle.css             # Main stylesheet for all pages
└── README.md               # Project documentation
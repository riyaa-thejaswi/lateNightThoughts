# Late Night Thoughts 🌙

> *"Words kept close, left softly by the window."*

A minimalist, editorial digital poetry journal and literary portfolio website. Designed with clean serif typography, calming pastel palettes, and a tranquil atmosphere for quiet evening reading.

## 📖 Table of Contents

* [About the Project](#about-the-project)

* [Pages](#pages)

* [Tech Stack & Typography](#tech-stack--typography)

* [Features](#features)

* [File Structure](#file-structure)

* [Getting Started](#getting-started)

* [Customization](#customization)

* [License](#license)

## 🕯️ About the Project

**Late Night Thoughts** is a multi-page, minimalist static website designed to house personal poetry, late-night reflections, and creative writing.

### Core Intentions

* **Editorial Atmosphere:** High-contrast serif headlines paired with airy whitespace to evoke the intimacy of a physical print journal.

* **Distraction-Free Reading:** Calm color transitions between sky blue, warm sage, and clean white backgrounds.

* **Lightweight Architecture:** Fast load times with zero frameworks or runtime overhead.

## 📄 Pages

The site is split across several dedicated HTML pages:

| File Name | Page Description | Key Elements | 
 | ----- | ----- | ----- | 
| `index.html` | Primary Landing Page | Hero slider, 2-column poem index, About teaser, 4-photo collage strip, newsletter form, contact form, editorial footer. | 
| `about.html` | Extended About Page | Author reflections, background narrative, and reading imagery. | 
| `contact.html` | Dedicated Mailbox | Information on correspondence cadence, direct mail link, and clean form inputs. | 
| `archive.html` | Complete Catalog | Chronological collection of all published poems using the index page's two-column list. | 
| `doWeEver.html` | Poem Page | Features starry night hero banner, centered stanzas, and poem metadata. | 
| `trustTheFearToFall.html` | Poem Page | Features sepia hillside hero banner, accent lines, and poem body. | 
| `aHeartForAHeart.html` | Poem Page | Features winter twilight banner, cold-season stanzas, and author sign-off. | 

## 🎨 Tech Stack & Typography

### Technologies

* **Markup:** Semantic [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5?utm_source=gemini)

* **Styling:** Vanilla [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS?utm_source=gemini) (CSS Grid, Flexbox, Custom Properties, Media Queries)

* **Scripting:** Vanilla JavaScript (DOM manipulation, carousel state, dynamic footer dates, scroll behavior)

### Fonts & Resources

* **Headings & Poetry:** [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond?utm_source=gemini) (weights: 300, 400, 500, italic) via Google Fonts.

* **Body & Navigation:** [Inter](https://fonts.google.com/specimen/Inter?utm_source=gemini) (weights: 300, 400, 500) via Google Fonts.

* **Imagery:** Curated imagery styled with responsive `object-fit: cover` ratios.

## ✨ Features

* **Interactive Hero Carousel:**

  * Forward/backward navigation using arrow buttons that fade in smoothly upon cursor hover.

  * Interactive dot pagination for direct slide jumping.

  * Smooth active transitions between slides.

* **Responsive 4-Photo Collage:**

  * 4-column edge-to-edge layout on desktop screens.

  * Automatically wraps to a 2x2 grid on tablets.

  * Switches to a single-column layout on smaller mobile devices.

* **Form Interactivity:**

  * Clean inline newsletter subscription block in the "Letters" section.

  * Structured "Quiet notes" form with client-side event handlers and response messaging.

* **Consistent Editorial Footer:**

  * Return-home / return-to-archive navigation.

  * Auto-updating copyright year powered by JavaScript (`new Date().getFullYear()`).

  * Colophon and typography credits.

## 📂 File Structure

```
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
├── mystyle.css             # Unified stylesheet for all pages
└── README.md               # Project documentation

```

## 🚀 Getting Started

### Prerequisites

No package managers, build tools (like npm or Vite), or server installations are required to run this project. Any modern web browser (Google Chrome, Firefox, Safari, Edge) will work out of the box.

### Local Setup

1. **Clone or Download the Repository:**

   * If using Git:

     ```
     git clone https://github.com/your-username/late-night-thoughts.git
     cd late-night-thoughts
     
     ```

   * If downloading as a ZIP:
     Extract the folder to your preferred directory.

2. **Open the Website:**

   * Double-click `index.html` to open it directly in your default browser.

   * Alternatively, right-click `index.html`, select **Open With**, and choose your browser of choice.

3. **(Optional) Run with Live Server:**
   If you use VS Code for editing, install the **Live Server** extension, right-click `index.html`, and click **Open with Live Server** to preview changes in real time.

## ✏️ Customization

### Adding a New Poem Page

1. Duplicate an existing poem file (e.g., `doWeEver.html`) and rename it (e.g., `newPoem.html`).

2. Update the `<title>` tag, hero banner image, title text, and stanzas.

3. Add the new poem link to both `index.html` and `archive.html`:

   ```
   <div class="poem-item">
     <a href="newPoem.html" class="poem-title">Your Poem Title</a>
     <span class="poem-date">Month DD, YYYY</span>
   </div>
   
   ```

### Modifying Color Variables

All primary theme colors are centralized at the top of `mystyle.css`:

```
:root {
  --sky-blue: #9dc7e6;       /* Hero & About background */
  --bg-sage: #f2f5f3;        /* Contact section & footer tint */
  --white: #ffffff;          /* Poems & Letters section */
  --text-dark: #111417;      /* Primary text and borders */
  --text-muted: #5e6b77;     /* Dates, subtext, and captions */
}

```

### Adding Slides to the Hero Carousel

In `index.html`, add a new `<img>` inside `.carousel-container` and a corresponding `<button>` inside `.dots-indicator`:

```
<!-- Inside .carousel-container -->
<img class="slide" src="YOUR_IMAGE_URL" alt="Description" />

<!-- Inside .dots-indicator -->
<button class="dot" data-index="2" aria-label="Slide 3"></button>

```

## 📄 License

* **Poetry & Written Content:** Copyright © Late Night Thoughts. All rights reserved. Reproduction or redistribution of original poems without prior written permission is prohibited.

* **Code & Layout Design:** Released under the [MIT License](https://opensource.org/licenses/MIT?utm_source=gemini). You are welcome to use, modify, and build upon the HTML/CSS templates for your own personal projects.
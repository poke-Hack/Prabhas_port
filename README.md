# 🌟 Rebel Star Prabhas | Official Fan Space

A fully responsive, feature-rich fan website dedicated to South Indian superstar **Prabhas**, built with pure HTML, CSS, and Vanilla JavaScript.

---

## 📋 Table of Content

- [Overview](#overview)
- [Features](#features)
- [Sections](#sections)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [License](#license)

---

## 🎬 Overview

This is a single-page fan website for Prabhas (the "Rebel Star" of Indian cinema), featuring his biography, filmography, photo gallery, news, merchandise store, fan forum, polls, events, and more. The site is designed with a cinematic dark/red theme and smooth animations throughout.

---

## ✨ Features

- **Fully Responsive** — works on desktop, tablet, and mobile devices
- **Sticky Navigation** — fixed header with smooth scroll behavior
- **Hero Section** — full-screen parallax background with call-to-action buttons
- **Movie Filter** — filter filmography by category (All, Action, Romance, Pan-India)
- **Interactive Gallery** — filterable photo gallery with lightbox support
- **Fan Art Upload** — form for fans to submit their artwork
- **News & Social Feeds** — latest news cards and live social media stats
- **Merchandise Store** — product cards with Add-to-Cart functionality and cart modal
- **Fan Forum** — post and view fan comments in real time
- **Polls** — animated voting bars with live interaction
- **Events Calendar** — upcoming fan events and premiere listings
- **Newsletter Subscription** — email sign-up form
- **Contact Form** — fan message submission
- **Back-to-Top Button** — smooth scroll back to the top
- **Toast Notifications** — slide-in feedback messages for user actions

---

## 📄 Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen banner with Prabhas title and quick-link icons |
| **About** | Biography, timeline of career milestones, and fun facts |
| **Movies** | Filterable filmography grid with poster, year, role, and ratings |
| **Gallery** | Photo grid with category filters and lightbox integration |
| **News** | Latest news cards + Instagram and Twitter social feed stats |
| **Store** | Merchandise cards (T-shirts, posters, etc.) with cart system |
| **Forum** | Fan discussion board — read and post messages |
| **Polls** | Animated fan poll with vote buttons |
| **Events** | Upcoming events/screenings with date badges |
| **Newsletter** | Email subscription form |
| **Contact** | Contact form with name, email, subject, and message fields |
| **Footer** | Links, social icons, and copyright |

---

## 🛠️ Technologies Used

- **HTML5** — semantic markup and structure
- **CSS3** — custom properties (CSS variables), Flexbox, CSS Grid, animations
- **JavaScript (ES6+)** — DOM manipulation, event handling, dynamic content rendering
- **Font Awesome 6.4** — icon library
- **Google Fonts** — Poppins and Cinzel typefaces
- **Lightbox2** — image lightbox for gallery

---

## 🚀 Getting Started

No build tools or package managers required. Simply open the file in a browser:

```bash
# Clone or download the repository
git clone https://github.com/your-username/prabhas-fan-site.git

# Open in browser
open prabhas.html
```

Or just double-click `prabhas.html` to launch it in your default browser.

> **Note:** Some features (like the gallery lightbox) may require the page to be served over HTTP. You can use a simple local server:
> ```bash
> npx serve .
> # or
> python -m http.server 8000
> ```

---

## 📁 File Structure

```
prabhas-fan-site/
│
└── prabhas.html          # Main (and only) file — all HTML, CSS & JS inline
```

All styles and scripts are embedded directly within `prabhas.html`, making it a single self-contained file with no external local assets required.

---

## 🎨 Customization

### Color Theme
Edit the CSS variables at the top of the `<style>` block:

```css
:root {
    --primary: #d32f2f;        /* Main red */
    --primary-dark: #9a0007;   /* Hover red */
    --primary-light: #ff6659;  /* Light red */
    --accent: #ffcc00;         /* Yellow accent */
    --secondary: #222;         /* Dark background */
}
```

### Adding Movies
In the JavaScript section, find the `moviesData` array and add a new object:

```javascript
{
    title: "Movie Title",
    year: 2024,
    role: "Character Name",
    category: "action",    // action | romance | pan-india
    rating: "8.5",
    image: "https://your-image-url.jpg"
}
```

### Adding Products
Find the `productsData` array in JavaScript and append:

```javascript
{
    name: "Product Name",
    price: 499,
    image: "https://your-image-url.jpg"
}
```

---

## 📦 Dependencies (CDN)

All external libraries are loaded via CDN — no local installation needed.

| Library | Version | Purpose |
|---|---|---|
| Font Awesome | 6.4.0 | Icons |
| Google Fonts (Poppins) | latest | Body font |
| Google Fonts (Cinzel) | latest | Heading font |
| Lightbox2 | 2.11.3 | Gallery lightbox |

---

## 📄 License

This project is created for fan and educational purposes only. All references to Prabhas, his films, and related media are the property of their respective owners.

---

> *"The Rebel Star of Indian Cinema"* 🌟

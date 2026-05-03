<div align="center">

# 🌟 Rebel Star Prabhas — Official Fan Space

**A cinematic, fully responsive fan website dedicated to South Indian superstar Prabhas.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com)

> *"The Rebel Star of Indian Cinema"* 🎬

</div>

---

## 📖 Overview

This is a single-page fan website for **Prabhas** — the Pan-India superstar known for *Baahubali*, *Saaho*, *Radhe Shyam*, *Adipurush*, and *Kalki 2898 AD*. Built entirely with pure HTML, CSS, and Vanilla JavaScript — no frameworks, no build tools. It features a **cinematic dark/red theme**, smooth animations, and a rich set of interactive sections designed to celebrate his legacy.

---

## ✨ Features at a Glance

| Feature | Details |
|---|---|
| 📱 Fully Responsive | Adapts seamlessly to desktop, tablet, and mobile |
| 🎯 Sticky Navigation | Fixed header with smooth scroll behavior |
| 🖼️ Hero Section | Full-screen parallax banner with CTA buttons |
| 🎬 Movie Filter | Filter filmography by genre (All / Action / Romance / Pan-India) |
| 🖼️ Interactive Gallery | Filterable photo grid with Lightbox2 support |
| 🎨 Fan Art Upload | Form for fans to submit their original artwork |
| 📰 News & Social Feeds | Latest news cards with live social media stats |
| 🛒 Merchandise Store | Product cards with Add-to-Cart + cart modal |
| 💬 Fan Forum | Post and view fan discussions in real time |
| 📊 Polls | Animated live voting bars |
| 📅 Events Calendar | Upcoming fan events and premiere listings |
| 📬 Newsletter | Email subscription form |
| ✉️ Contact Form | Fan message submission with full fields |
| 🔔 Toast Notifications | Slide-in feedback messages for user actions |
| ⬆️ Back-to-Top Button | Smooth scroll back to the top |

---

## 📄 Sections

| # | Section | Description |
|---|---|---|
| 1 | **Hero** | Full-screen banner with Prabhas title and quick-link icons |
| 2 | **About** | Biography, career milestones timeline, and fun facts |
| 3 | **Movies** | Filterable filmography grid — poster, year, role, and rating |
| 4 | **Gallery** | Photo grid with category filters and Lightbox integration |
| 5 | **News** | Latest news cards + Instagram & Twitter social feed stats |
| 6 | **Store** | Merchandise cards (T-shirts, posters, etc.) with a cart system |
| 7 | **Forum** | Fan discussion board — read and post messages |
| 8 | **Polls** | Animated fan poll with vote buttons |
| 9 | **Events** | Upcoming events/screenings with date badges |
| 10 | **Newsletter** | Email subscription form |
| 11 | **Contact** | Contact form — name, email, subject, and message |
| 12 | **Footer** | Links, social icons, and copyright |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Custom properties, Flexbox, Grid, and animations |
| **JavaScript (ES6+)** | DOM manipulation, event handling, dynamic rendering |
| **Font Awesome 6.4** | Icon library |
| **Google Fonts — Poppins** | Body typeface |
| **Google Fonts — Cinzel** | Display / heading typeface |
| **Lightbox2 2.11.3** | Gallery image lightbox |

---

## 🚀 Getting Started

No build tools, package managers, or environment setup required.

**Option 1 — Just open it:**
```bash
# Clone the repository
git clone https://github.com/your-username/prabhas-fan-site.git

# Open directly in your browser
open prabhas.html
```
Or simply double-click `prabhas.html`.

**Option 2 — Local server (recommended for gallery lightbox):**
```bash
# Using Node.js
npx serve .

# Using Python
python -m http.server 8000
```
Then visit `http://localhost:8000/prabhas.html`.

> **Note:** The gallery lightbox requires the page to be served over HTTP rather than opened as a local file.

---

## 📁 File Structure

```
prabhas-fan-site/
└── prabhas.html      ← Everything is here: HTML + CSS + JS, all inline
```

This is a **zero-dependency, single-file project**. All styles and scripts are embedded directly in `prabhas.html` — no external local assets needed.

---

## 🎨 Customization

### 🎨 Color Theme
Find the CSS variables at the top of the `<style>` block and update them:

```css
:root {
    --primary:       #d32f2f;   /* Main red */
    --primary-dark:  #9a0007;   /* Hover / active red */
    --primary-light: #ff6659;   /* Light red accents */
    --accent:        #ffcc00;   /* Yellow accent */
    --secondary:     #222222;   /* Dark background */
}
```

### 🎬 Adding a Movie
Locate the `moviesData` array in the JavaScript section and append a new object:

```javascript
{
    title:    "Movie Title",
    year:     2025,
    role:     "Character Name",
    category: "action",       // "action" | "romance" | "pan-india"
    rating:   "9.0",
    image:    "https://your-image-url.jpg"
}
```

### 🛒 Adding a Product
Locate the `productsData` array and append:

```javascript
{
    name:  "Product Name",
    price: 499,
    image: "https://your-image-url.jpg"
}
```

---

## 📦 CDN Dependencies

All external libraries load via CDN — no local installation needed.

| Library | Version | CDN Purpose |
|---|---|---|
| Font Awesome | 6.4.0 | Icons |
| Google Fonts — Poppins | latest | Body font |
| Google Fonts — Cinzel | latest | Heading font |
| Lightbox2 | 2.11.3 | Gallery lightbox |

---

## 🤝 Contributing

Contributions are welcome! To suggest changes or improvements:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add: your feature description"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## ⚠️ Disclaimer

This project is created for **fan and educational purposes only**. All references to Prabhas, his films, images, and related media are the property of their respective owners. This site is not affiliated with or endorsed by Prabhas or his management.

---

## 📄 License

Distributed under the [MIT License](LICENSE). See `LICENSE` for more information.

---

<div align="center">

Made with ❤️ for fans of the **Rebel Star** — Prabhas 🌟

</div>

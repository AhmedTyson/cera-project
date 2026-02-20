# <img src="https://api.iconify.design/lucide:palette.svg?color=%238A2BE2" width="32" height="32" align="center" /> Artistic Workshop

> **A multi-page static website for an artistic workshop studio.**
> Semantic HTML and CSS architecture focused on workshops, products, and creative booking.

<div align="center">

| Project Status | Type                                                                                      | Structure                                                                                        | Deployment           |
| :------------- | :---------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------- | :------------------- |
| `STABLE`       | ![Static Site](https://img.shields.io/badge/Type-Static_Site-lightgrey?style=flat-square) | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | `Local/GitHub Pages` |

</div>

---

## <img src="https://api.iconify.design/lucide:list.svg?color=%238A2BE2" width="20" height="20" align="center" /> Table of Contents

- [Overview](#overview)
- [Pages](#-pages)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)

---

## Overview

This project is a complete multi-page website for a fictional artistic workshop brand — built as an early frontend development exercise. The goal was to demonstrate structured multi-page site architecture, semantic HTML5 markup, CSS layout techniques, and page-to-page navigation. The site covers the typical surface area of a small creative business: a homepage, product catalog, workshops, contact, about, and login pages.

No JavaScript frameworks or CSS preprocessors are used — the entire site is authored in raw HTML and CSS, keeping the focus on frontend fundamentals.

---

---

## <img src="https://api.iconify.design/lucide:file-text.svg?color=%238A2BE2" width="20" height="20" align="center" /> Pages

| Page          | Route            | Description                                         |
| ------------- | ---------------- | --------------------------------------------------- |
| **Home**      | `index.html`     | Landing page with brand introduction and highlights |
| **Products**  | `products.html`  | Catalog of artistic products with visual layout     |
| **Workshops** | `workshops.html` | Workshop listings, schedules, and details           |
| **About Us**  | `aboutus.html`   | Brand story, mission, and team information          |
| **Contact**   | `contact.html`   | Contact form and studio location                    |
| **Login**     | `login.html`     | Styled member login page                            |

---

---

## <img src="https://api.iconify.design/lucide:cpu.svg?color=%238A2BE2" width="20" height="20" align="center" /> Tech Stack

| Layer            | Technology                                   |
| ---------------- | -------------------------------------------- |
| **Structure**    | HTML5 (Semantic elements, forms, navigation) |
| **Styling**      | CSS3 (Flexbox, custom layout, typography)    |
| **Assets**       | Custom images in `/images` directory         |
| **Dependencies** | None — zero external libraries               |

---

---

## <img src="https://api.iconify.design/lucide:folder-tree.svg?color=%238A2BE2" width="20" height="20" align="center" /> Project Structure

```
artistic-project/
├── index.html           # Home landing page
├── products.html        # Product catalog
├── workshops.html       # Workshop listings
├── aboutus.html         # About the studio
├── contact.html         # Contact form
├── login.html           # Login page
│
├── css/                 # Stylesheets
│   └── style.css        # Global styles
│
└── images/              # Image assets
    └── [product and brand imagery]
```

---

---

## <img src="https://api.iconify.design/lucide:rocket.svg?color=%238A2BE2" width="20" height="20" align="center" /> Getting Started

```bash
# Clone the repository
git clone https://github.com/AhmedTyson/artistic-project.git

# Navigate to the directory
cd artistic-project

# Open in browser
start index.html
```

> No dependencies or build step required. Open any page directly in a modern browser.

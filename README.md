# My Experiential Learning Journey Webpage

This repository contains a **single HTML file** that renders a complete, interactive portfolio webpage. The site details my experiential learning (EL) journeys to Pune (Oct 2025) and Hyderabad (Nov 2025).

This project was developed as part of an academic activity. The primary constraint and challenge was to build the entire website—including all styles, scripts, and interactive logic—within a **single `.html` file**, without any external `.css` or `.js` files.

## Live Demo

You can view the live, hosted version of this project here:

[**https://your-username.github.io/your-repo-name/**](https://your-username.github.io/your-repo-name/)

*(Note: Replace the URL above with your actual GitHub Pages link after hosting.)*

## Features

This single file demonstrates a wide range of modern web technologies:

* **Fully Responsive Design:** Adapts fluidly to all screen sizes, from mobile to desktop.
* **Dark/Light Mode:** A theme toggle that respects user's system preference (`prefers-color-scheme`) and saves their choice in `localStorage`.
* **HTML5 Semantic Elements:** Uses `<header>`, `<footer>`, `<main>`, `<article>`, `<section>`, and `<figure>` for a clean and accessible structure.
* **Interactive Photo Galleries:**
    * Each of the 10 gallery slots can hold multiple images.
    * A "cover" image is displayed, and hovering reveals a grid of additional photos for that slot.
* **Fullscreen Lightbox:** Clicking on *any* gallery image opens it in a full-screen, high-resolution overlay.
* **CSS 3D Transforms & Animations:** Smooth, hardware-accelerated animations on image hover, button presses, and page load.
* **HTML5 Canvas Animation:** A dynamic, animated logo graphic is rendered in the "Reflections" section using the Canvas API.
* **Live Contact Form:** A "Share Your Story" form that uses FormSubmit to send its contents directly to an email address.
* **Web Storage:** The contact form uses `localStorage` to "Remember" the user's name if they check the box.

## Technology Stack

* **HTML5:** For all content and semantic structure.
* **Tailwind CSS (via CDN):** Used exclusively for all styling, layout, responsive design, and dark mode theming.
* **JavaScript (ES6+):** All JavaScript is contained within a single `<script>` tag at the bottom of the HTML file. It powers:
    * Dark Mode Toggle & Web Storage
    * Fullscreen Lightbox Logic
    * Canvas Animation Loop
    * Contact Form "Remember Me" Feature

## How to View Locally

1.  Clone or download this repository.
2.  Since all content is in one file, simply open the `learning-journey.html` (or `index.html`) file directly in your web browser.

---

*This webpage was created by Shivakant Kurmi (23BCG10140), a B.Tech CSE (Gaming Technology) student at VIT Bhopal University.*

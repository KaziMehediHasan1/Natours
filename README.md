# Natours - Advanced CSS & Sass Project

Natours is a high-end, responsive landing page for an outdoorsy travel company. This project was developed to master **Advanced CSS** techniques, **Sass** architecture, and modern web design principles.



## 🚀 Purpose & Learning Goals
The main goal of this project was to move beyond basic CSS and implement professional-grade styling workflows. Key focus areas included:
* **Advanced CSS Animations:** Using `@keyframes` and transition effects for a premium feel.
* **The Sass 7-1 Pattern:** Organizing styles into a scalable folder structure.
* **Responsive Design:** Implementing 'Desktop-First' and 'Mobile-First' strategies using mixins.
* **BEM Methodology:** Writing clean, maintainable, and scalable class names.

## ✨ Key Features
* **Custom Grid System:** Built using Float layouts (and modern Flexbox/Grid where applicable).
* **Complex UI Elements:** Custom-built navigation menus, animated buttons, and "card flip" effects.
* **Hero Header:** A stunning hero section with a clip-path polygon shape.
* **Booking Section:** A functional-looking form with custom radio buttons and inputs.
* **Optimized Images:** Implementation of responsive images in HTML and CSS.

## 🛠️ Tech Stack
* **HTML5:** Semantic markup for better SEO and accessibility.
* **CSS3:** Advanced features like `clip-path`, `background-blend-mode`, and `filter`.
* **Sass:** Utilizing variables, mixins, functions, and nesting.
* **NPM Scripts:** For compiling Sass to CSS and auto-prefixing.

## 📂 Project Structure (Sass 7-1)
I followed the professional 7-1 pattern to keep the codebase clean:
```text
sass/
|-- abstracts/   (Variables, mixins)
|-- base/        (Reset, typography, animations)
|-- components/  (Buttons, cards, composition)
|-- layout/      (Header, footer, grid)
|-- pages/       (Home styles)
|-- themes/      (Theme specific styles)
|-- vendors/     (External CSS)

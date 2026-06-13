# Advanced CSS3 & Responsive Portfolio Website

## Overview

This project transforms a semantic HTML5 portfolio into a visually appealing and fully responsive website using advanced CSS3 features and modern layout techniques. The website follows accessibility standards and adapts seamlessly across mobile, tablet, and desktop devices.

---

## Features

* Semantic HTML5 structure
* CSS Grid for page layouts
* Flexbox for navigation and component alignment
* Mobile-first responsive design
* Custom CSS variables for theme management
* Light and Dark mode support
* Accessibility-focused design
* SEO-friendly pages
* Keyboard navigation support

---

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Responsive Media Queries
* CSS Variables

---

## Project Structure

```text
advanced-responsive-portfolio-css3/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
└── README.md
```

---

## Pages

### Home Page

* Welcome section
* Introduction to the portfolio

### About Page

* Professional information
* Skills and specialization

### Projects Page

* Project showcase
* Accessible project links

### Contact Page

* User-friendly contact section
* Accessible form elements

---

## Advanced CSS Features

### CSS Grid

Used to create responsive two-dimensional layouts.

### Flexbox

Used for navigation alignment and component organization.

### Responsive Media Queries

Implemented using a mobile-first approach:

* Mobile devices
* Tablets
* Desktop screens

### CSS Variables

```css
:root {
  --bg-color: #ffffff;
  --text-color: #222;
  --primary-color: #0055aa;
  --accent-color: #ff9900;
}
```

### Dark Mode Support

```css
[data-theme="dark"] {
  --bg-color: #121212;
  --text-color: #f0f0f0;
  --primary-color: #3399ff;
  --accent-color: #ffcc00;
}
```

---

## Layout Architecture

### CSS Grid

```css
main {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}
```

### Flexbox Navigation

```css
nav ul {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}
```

---

## Responsive Breakpoints

### Tablet

```css
@media (min-width: 601px) {
  main {
    grid-template-columns: 1fr 1fr;
  }
}
```

### Desktop

```css
@media (min-width: 1025px) {
  main {
    grid-template-columns: repeat(3, 1fr);
  }
}
```

---

## Accessibility Features

* ARIA labels
* Semantic HTML5 elements
* Keyboard navigation support
* Focus indicators
* Accessible links and buttons
* Screen-reader friendly structure

---

## Expected Outcome

A pixel-perfect, highly responsive portfolio website that adapts flawlessly across:

* Mobile Devices
* Tablets
* Laptops
* Desktop Screens

---

## Author

**Challa Pradeep**

Aspiring Web Developer

---

## License

This project is created for educational and internship purposes.

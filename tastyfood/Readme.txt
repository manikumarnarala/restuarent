# 🍽 Tasty Food Template

## 📖 Overview
This is a responsive restaurant website template designed to showcase **food menus, chefs, events, testimonials, and booking functionalities**.  
It is built using **HTML5, CSS3, Bootstrap 5**, and various frontend libraries for **animations, sliders, and icons**.

---

## 🌐 Technologies Used

### 📝 HTML
**HTML5 Semantic Tags**
- `<header>` → Top navigation and branding  
- `<nav>` → Main navigation bar  
- `<section>` → Each content section (Hero, About, Menu, Testimonials, Events, Chefs, Book a Table)  
- `<main>` → Main content container  
- `<footer>` → (Optional) Footer content  
- `<div>` → Generic container  
- `<ul>, <li>` → Lists for navigation, menu tabs, and dropdowns  
- `<a>` → Hyperlinks and button links  
- `<img>` → Images for menus, chefs, and events  
- `<p>` → Paragraph text  
- `<h1>–<h4>` → Headings  
- `<span>` → Inline styling or emphasis  
- `<form>, <input>` → Booking form  
- `<i>` → Icons (Bootstrap Icons)  

**Attributes Used**
- `class` / `id` → For CSS and JS targeting  
- `data-aos` → For animation on scroll  
- `data-bs-toggle` / `data-bs-target` → For Bootstrap tabs  
- `data-purecounter-start`, `data-purecounter-end`, `data-purecounter-duration` → For animated counters  
- `href`, `src`, `alt` → Links, images, and accessibility  
- `style` → Inline background images  

---

### 🎨 CSS
**Bootstrap Classes**
- `d-flex`, `align-items-center`, `justify-content-between` → Flexbox utilities  
- `container`, `container-fluid` → Layout containers  
- `row`, `col-lg-4`, `col-md-6`, etc. → Grid system  
- `section-bg` → Background styling for sections  
- `btn-book-a-table`, `btn-watch-video` → Buttons  
- `nav-tabs`, `nav-link`, `active`, `show` → Tab navigation  

**Custom CSS**
- Main custom styles stored in: `assets/css/main.css`  
- Section-specific backgrounds using inline styles:
  ```html
  style="background-image: url(assets/img/about.jpg);"



⚙️ JavaScript & Libraries

Bootstrap 5 JS → Tabs, dropdowns, modals, and responsive navbar

AOS (Animate On Scroll) → Smooth fade-in and zoom animations

Swiper.js → Sliders/carousels in Events and Testimonials sections

Glightbox → Lightbox for menu images and video play buttons

PureCounter.js → Animated counters in Stats section

Bootstrap Icons → Star ratings, social media, and UI icons

🏗 Structure of Website Sections
🔝 Header / Navbar

Logo (<h1> text-based)

Menu links (Home, About, Menu, Events, Chefs, Gallery, Contact)

Dropdown menu with multi-level nested links

Mobile menu toggle (bi-list / bi-x)

🎯 Hero Section

Full-width introduction with heading, description, CTA buttons

Image on the right side

Animated scroll effects (data-aos)

ℹ️ About Section

Two-column layout: Image + Content

Booking number and embedded video link

List of features with check icons

⭐ Why Us Section

Reasons to choose the restaurant

Icon boxes with descriptions

📊 Stats Counter Section

Clients, Projects, Hours of Support, Workers

Uses PureCounter for animation

🍴 Menu Section

Tab-based menu (Starters, Breakfast, Lunch, Dinner)

Menu items with images, ingredients, and prices

Lightbox image preview

💬 Testimonials Section

Swiper slider for client testimonials

Includes images, quotes, stars, names, and positions

🎉 Events Section

Slider showing different events with price and description

Background images for each event

👨‍🍳 Chefs Section

Profiles with images, social links, names, roles, and descriptions

📅 Book a Table Section

Two-column layout: Image + Booking form

Form validation using data-rule attributes

Submits to forms/book-a-table.php
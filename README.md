# 🌄 Mobile First - Wanderly

**(Responsive Website · Mobile First · Responsive Images · CSS Media Queries · JavaScript)**

A responsive travel-themed website built with a Mobile First approach.  
This educational portfolio project focuses on creating a responsive travel website with a clean and modern design, responsive layouts, optimized images, and interactive mobile navigation.

The project currently contains the homepage and will be gradually expanded with additional pages such as Destinations, About Us, and Contact.

[🔗 **Live Preview**](https://karchmarek.github.io/Mobile-first-Wanderly/)

---

## 🚀 Project Goal

The goal of this project is to practice building a responsive website using a Mobile First approach and gradually introduce JavaScript for interactive functionality.

The project focuses on:

- Mobile First development
- Responsive layouts
- Responsive images
- CSS media queries
- Semantic HTML
- Interactive navigation with JavaScript
- Clean and reusable CSS structure
- Building a multi-page website step by step

---

## ✨ Features

- 📱 **Responsive Mobile First design**
- 🧭 **Responsive navigation**
- 🍔 **Interactive hamburger menu on mobile**
- ❌ **Dynamic hamburger / close icon switching**
- 🖼️ **Responsive hero images**
- 🌄 **Different image sizes for different screen widths**
- 🗺️ **Popular destinations section**
- 📐 **Responsive layout using Flexbox**
- 🎨 **Custom typography and travel-themed design**
- ♿ **Basic accessibility attributes for interactive elements**
- 📱 **Responsive breakpoints for mobile, tablet and desktop**

---

## 🛠️ Tech Stack

- **HTML5** – Semantic page structure and content.
- **CSS3** – Mobile First styling, responsive layouts, media queries and Flexbox.
- **JavaScript** – Interactive mobile navigation and dynamic menu icon switching.
- **Normalize.css** – Consistent default styling across browsers.
- **Font Awesome** – Icons used throughout the interface.
- **Google Fonts** – Source Sans 3 typography.

---

## 📱 Responsive Design

The website is developed using a Mobile First approach.

### Breakpoints

- **Mobile:** default styles
- **Mobile L:** `425px`
- **Tablet:** `768px`
- **Desktop:** `1024px`
- **Large Desktop:** `1440px`

The layout, typography, navigation and image sizes adapt to the available screen width.

---

## 🖼️ Responsive Images

Different image versions are used depending on the screen size:

- `small` – mobile devices
- `medium` – tablets
- `large` – desktop screens

The hero section and destination cards use different image sizes through CSS media queries.

Example:

```css
.hero {
    background-image: url("../img/hero-small.webp");
}

@media (min-width: 768px) {
    .hero {
        background-image: url("../img/hero-medium.webp");
    }
}

@media (min-width: 1024px) {
    .hero {
        background-image: url("../img/hero-large.webp");
    }
}
```

---

## 🔮 Future Development

The website will be gradually expanded with additional pages and functionality.

#### Planned pages:

- 🗺️ **Destinations**
- 👤 **About Us**
- 📩 **Contact**

Additional JavaScript functionality may also be added as the project develops.

---

## 📌 Project Status

**Currently:** Homepage completed and responsive.

**Next:** Development of additional website pages and functionality.
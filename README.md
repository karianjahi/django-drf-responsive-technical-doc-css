# Django DRF Responsive Technical Docs - CSS Project

This project, titled **responsive-technical-docs-css**, is a responsive and interactive **technical documentation page** built using only HTML and CSS. The documentation focuses on Django REST Framework (DRF), demonstrating how to structure, navigate, and display content in a clean, user-friendly, and accessible format.

---

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Responsive Behavior](#responsive-behavior)
- [Navigation Highlight](#navigation-highlight)
- [How to Use](#how-to-use)
- [License](#license)

---

## 📌 Overview

This project showcases a responsive technical documentation layout, modeled after documentation pages like MDN and freeCodeCamp. It contains detailed sections explaining key concepts in Django REST Framework (DRF), such as Serializers, ViewSets, Authentication, and Testing.

The page is fully responsive and includes a sidebar navigation menu that is always visible on larger screens and easy to access on smaller devices.

---

## ✅ Features

- Fully **responsive layout** using CSS media queries
- **Fixed navigation bar** for easy access to all documentation sections
- Uses `:target` selector to highlight the currently focused section when navigated via anchor links
- Code blocks styled with `<pre><code>` elements for proper formatting
- Semantic HTML structure for accessibility and SEO
- Modern, clean, and readable typography and layout

---

## 🛠 Technologies Used

- HTML5
- CSS3 (Media Queries, Flexbox, Pseudo-selectors)
- No JavaScript or external libraries

---

## 📱 Responsive Behavior

The layout adapts across three breakpoints:

- **Mobile (≤ 768px)**:
  - Main content resizes to 358px width
  - Content stacks vertically
- **Tablet (769px to 1199px)**:
  - Main content resizes to 675px
- **Desktop (≥ 1200px)**:
  - Full layout with sidebar navigation on the left
  - Content area centered and bordered

---

## 🎯 Navigation Highlighting

When a user clicks a link in the navigation menu:

- The corresponding section is scrolled into view
- That section is styled with a dark background (`:target`)
- The color and contrast change visually indicates the active section

```css
.main-section:target {
    background-color: rgb(43, 23, 91);
    color: white;
}
```
This is purely CSS-based and uses the :target pseudo-class with anchor links (#section-id)

## 🚀 How to Use

1. Clone the Repository

```
git clone https://github.com/karianjahi/responsive-technical-docs-css.git
cd responsive-technical-docs-css
```

2. Open in Browser

Simply open index.html in your browser.

## 📝 License
This project is licensed under the MIT License. You are free to use, modify, and distribute it as needed.

## 📫 Feedback and Contributions
If you find bugs or want to suggest improvements, feel free to open an Issue or a Pull Request.

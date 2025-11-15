# Assignment 2

# 🌱 **PROJECT SEED — LanguageLift**

**LanguageLift** is a fictional AI-powered language learning platform designed to help learners gain fluency faster through smart, adaptive tools. The platform provides multilingual learning support, pronunciation coaching, grammar correction, and personalized study paths — all powered by an AI mentor. Whether a user wants to learn English for work, Japanese for travel, or Spanish for school, LanguageLift offers structured lessons, real-life practice scenarios, and interactive exercises.

The goal of LanguageLift is to make language learning **simple, accessible, and globally inclusive**, using intelligent feedback and a supportive community to help learners stay consistent and motivated.

---

# 🎨 **DESIGN RATIONALE — LanguageLift Website**

The LanguageLift mini-site is designed with clarity, accessibility, and modern UI principles. Below is the reasoning behind all major design choices:

### **1. High-Contrast Visual Theme**

A bold contrast palette of deep purples, bright yellows, and clean whites ensures:

* WCAG-compliant readability
* clear visual hierarchy
* standout interactive elements (buttons, cards, form fields)

This enhances accessibility for users with visual impairments and improves the overall aesthetic.

### **2. Semantic, Accessible Structure**

All content uses proper HTML5 semantics — `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<form>` — allowing:

* better screen-reader navigation
* improved keyboard traversal
* structured document flow

Forms use `<label>`, `<fieldset>`, `<legend>`, and `:focus-visible` for best accessibility.

### **3. CSS Grid for Global Layout**

CSS Grid provides a stable, responsive foundation for:

* hero section
* feature blocks
* plans
* form layout
* footer columns

Grid ensures even spacing and predictable scaling across all screen sizes.

### **4. Flexbox for Individual Components**

Flexbox is used inside cards, buttons, nav, and FAQs for:

* easy alignment
* flexible stacking
* smooth wrapping on mobile

This maintains usability even with dynamic content or long text.

### **5. Three Clear Breakpoints**

The interface adapts at:

* **Desktop (default)**
* **Tablet (max-width: 1024px)**
* **Mobile (max-width: 768px)**

Each breakpoint adjusts:

* grid columns
* spacing
* font scale
* navigation layout

This ensures the layout feels deliberate at every size, not “squeezed.”

### **6. CSS-Only Interactivity**

To keep compliance with the assignment restrictions (no JavaScript), interactivity is implemented using:

* hover lift effects
* animated buttons
* `<details>` and `<summary>` for FAQs
* focus-visible states
* card shadow transitions

This gives the site a dynamic feel without scripts.

### **7. Consistent Component Design System**

All components follow a shared set of design tokens:

* radius: soft, rounded corners
* spacing scale: xs, sm, md, lg
* typography: clean sans-serif
* shadows: small elevation for cards
* buttons: pill-shaped, high-contrast CTA styling

This ensures a cohesive, brand-consistent appearance.

### **8. Custom SVG Illustration**

A handcrafted SVG in the hero section:

* reinforces theme (language learning)
* adds meaningful visual interest
* loads instantly (vector-based)
* maintains crisp detail at all screen sizes

---

If you want, I can also create:

📌 A **Design System section** (color variables, typography, spacing tokens)
📌 A **Feature justification section** for a more academic-style README
📌 A **short version** of seed + rationale for class submissions

Just tell me!

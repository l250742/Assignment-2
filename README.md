# Assignment 2

# 🌱 **PROJECT SEED — LanguageLift**

**LanguageLift** is a fictional AI-powered language learning platform designed to help learners gain fluency faster through smart, adaptive tools. The platform provides multilingual learning support, pronunciation coaching, grammar correction, and personalized study paths — all powered by an AI mentor. Whether a user wants to learn English for work, Japanese for travel, or Spanish for school, LanguageLift offers structured lessons, real-life practice scenarios, and interactive exercises.

The goal of LanguageLift is to make language learning **simple, accessible, and globally inclusive**, using intelligent feedback and a supportive community to help learners stay consistent and motivated.

---

# 🎨 **DESIGN RATIONALE — LanguageLift Website**

1. **High-contrast color palette**
   Bold, accessible colors (deep purple, bright yellow, white) ensure strong visual contrast, improving readability, focus indicators, and overall accessibility in accordance with WCAG guidelines.

2. **Semantic HTML structure**
   The site uses `<header>`, `<main>`, `<section>`, `<article>`, `<form>`, and `<footer>` to organize content logically. This improves SEO, ensures better screen-reader interpretation, and creates a predictable document flow.

3. **CSS Grid for the main layout**
   Grid defines the large-scale structure of the page, including the hero section, feature area, pricing plans, and form layout. It provides consistent alignment and smooth responsiveness across breakpoints.

4. **Flexbox for internal component alignment**
   Inside cards, FAQs, buttons, and nav elements, Flexbox handles spacing, vertical alignment, and stacking on smaller screens. This keeps each component clean and adaptable without breaking.

5. **Three clear responsive breakpoints**

   * **Desktop (default)**: full layout, multi-column grid
   * **Tablet (max-width: 1024px)**: reduced grid columns, moderate scaling
   * **Mobile (max-width: 768px)**: stacked layout, simplified spacing and typography
     These ensure the layout remains intentional and easy to navigate on all device sizes.

6. **CSS-only interactivity**
   Without JavaScript, interactivity is achieved through:

   * hover animations
   * card elevation/shadow transitions
   * focus-visible styling for keyboard navigation
   * `<details><summary>` for expandable FAQs
     This adds engagement while staying within project restrictions.

7. **Accessible form design**
   All inputs use proper `<label>` associations, logical grouping with `<fieldset>` and `<legend>`, and visible focus indicators. Custom checkboxes and radio buttons are styled while maintaining keyboard and screen-reader compatibility.

8. **Consistent design system**
   The site uses unified values for spacing, border-radius, button shapes, shadows, and typography. This creates a cohesive brand identity and makes the UI easier for users to scan and understand.

9. **Custom SVG illustration**
   A lightweight, scalable SVG reinforces the language-learning theme. It loads quickly, remains crisp on all displays, and enhances visual branding without impacting performance.

---


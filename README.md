# Portfolio Project Milestone 3: Accessible & Designed

## 1. Accessibility Fixes & Verification (WAVE & WCAG AA)
- Verified page structure across all pages using the WAVE Web Accessibility Evaluation Tool; 0 errors and 0 contrast errors detected.
- Confirmed alternative text (`alt="Matthew Hair"`) on all visual profile images across pages.
- Verified semantic HTML5 landmark tags (`<header>`, `<nav>`, `<main>`, `<footer>`) and heading hierarchy (`<h1>` through `<h3>`) for screen reader navigation.
- Ensured body and header text colors meet WCAG AA contrast ratio standards (4.5:1 minimum).

## 2. Visual Design & Gestalt Principles
- **Proximity:** Grouped navigation links within a single `<nav>` container and structured featured content into distinct visual blocks with consistent padding and margin spacing.
- **Similarity:** Standardized typography, color palettes, link hover states, and header layouts across `index.html`, `projects.html`, and `about.html` for a cohesive user interface.
- **Continuity & Alignment:** Aligned all major text elements, headings, and images along a shared vertical grid line to create a natural visual path for the user's eye.

## 3. Accessible Contact Form
- Integrated an accessible form into `about.html` utilizing fieldsets, legends, explicit `<label for="...">` associations, and ARIA attributes for error messaging.

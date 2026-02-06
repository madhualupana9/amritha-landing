---
description: Repository Information Overview
alwaysApply: true
---

# Amritha Landing Page Information

## Summary
This repository contains a static landing page for **Amritha Advanced Rehabilitation & Elder Care**, a medical organization based in Hyderabad. The project focuses on providing a professional web presence to showcase assisted living and rehabilitation services.

## Structure
- **[./assets/](./assets/)**: Main directory for static assets.
    - **[./assets/css/](./assets/css/)**: Contains compiled and vendor stylesheets including `style.css`, `swiper-bundle.min.css`, and `scrollCue.css`.
    - **[./assets/fonts/](./assets/fonts/)**: Local web fonts and icon fonts.
    - **[./assets/images/](./assets/images/)**: Project images, including logos and promotional visuals.
    - **[./assets/js/](./assets/js/)**: JavaScript files including vendor libraries and `custom.js` for site interactivity.
- **[./index.html](./index.html)**: The main entry point of the landing page.
- **[./thankyou.html](./thankyou.html)**: Post-submission confirmation page.

## Language & Runtime
**Language**: HTML5, CSS3, JavaScript  
**Runtime**: Web Browser  
**Build System**: None (Direct static deployment)  
**Package Manager**: None (Dependencies are included locally in `assets/` or via CDN)

## Dependencies
**Main Dependencies**:
- **Bootstrap 5**: UI components and grid system.
- **Swiper**: Modern touch slider for carousels.
- **ScrollCue**: Scroll-triggered animations.
- **Lenis**: Smooth scrolling library.
- **fslightbox**: Lightbox functionality for images.
- **Ukiyo**: Parallax effects.
- **Font Awesome**: Icon library (CDN-based).
- **Tabler Icons**: SVG icon library.

## Usage & Operations
**Deployment**:
The project can be served using any standard web server (Apache, Nginx, or local development servers like Laragon).

**Key Files**:
- **[./index.html](./index.html)**: Primary file for content modifications.
- **[./assets/css/style.css](./assets/css/style.css)**: Main file for custom styling.
- **[./assets/js/custom.js](./assets/js/custom.js)**: Main file for custom interactive logic.

## Validation
**Verification Approach**:
As a static site, verification is performed through manual browser testing across different viewport sizes to ensure responsiveness and functionality of interactive elements (sliders, smooth scroll, etc.).

# Project: Alma Kasouha Portfolio

This project is a personal portfolio website for Alma Kasouha, showcasing her academic background, professional experiences, and skills in the agro-food industry.

## Project Overview

- **Purpose:** Professional portfolio and digital resume.
- **Technologies:** 
    - **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript.
    - **Icons:** Font Awesome.
    - **Fonts:** Google Fonts (Montserrat & Open Sans).
- **Architecture:** Single-page static website with scroll-reveal animations and a responsive design.

## Directory Structure

- `index.html`: Main entry point containing the structure and Tailwind configuration.
- `style.css`: Custom CSS for animations, glassmorphism effects, and timeline styling.
- `script.js`: JavaScript for scroll animations and dynamic navbar effects.
- `images/`: Directory containing profile pictures, project thumbnails, and favicon.
- `cv/`: Directory containing the downloadable PDF version of the CV.
- `CNAME`: Configuration for the custom domain `almakasouha.com`.

## Building and Running

### Development
Since this is a static website, no build process is required.
1. Open `index.html` directly in any modern web browser.
2. For a better experience, use a local development server like "Live Server" (VS Code extension) to see changes in real-time.

### Deployment
The project is designed to be hosted on static hosting services (e.g., GitHub Pages).
- Ensure the `CNAME` file contains the correct domain name for production.

## Development Conventions

- **Styling:** Primarily uses Tailwind CSS utility classes. Custom animations and complex styles should be added to `style.css`.
- **Animations:** Uses a custom `reveal` class in CSS combined with `script.js` to trigger animations on scroll.
- **Organization:** Keep images in the `images/` folder and document-related assets in their respective directories (like `cv/`).
- **Responsive Design:** Follow Tailwind's mobile-first approach.

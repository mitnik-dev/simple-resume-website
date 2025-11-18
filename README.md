# Simple Resume Website

## Overview
- Personal résumé site built with semantic HTML and a terminal-inspired aesthetic.
- Includes dedicated pages for résumé content, a tailored cover letter, and long-term career goals.
- Designed as a standalone static site that can be opened directly in any modern browser—no build tools required.

## Pages
- `pages/resume.html` – Primary résumé content with education, experience, skills, and contact details.
- `pages/cover-letter.html` – Internship-focused cover letter formatted in the same terminal layout.
- `pages/career-goals.html` – Narrative career roadmap plus a contact form that triggers an animated “asciiquarium” easter egg with synchronized audio.

## Features
- Terminal-style layout with animated cursor, faux window chrome, and custom scrollbar styling.
- Dark theme implemented via `assets/css/styles.css`, using flexbox to keep content centered and responsive.
- Navigation menu to jump between résumé, cover letter, and career goals pages.
- Auto-updating footer date rendered with vanilla JavaScript on each page.
- Interactive contact form that reveals an embedded video and audio clip when submitted.
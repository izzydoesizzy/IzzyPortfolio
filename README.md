# Izzy Portfolio

> A comprehensive personal portfolio site for Izzy Piyale-Sheard featuring work experience timeline, side projects showcase, public speaking history, testimonials, travel photography, Konami Code easter egg, and Google Maps contact section.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/IzzyPortfolio](https://izzydoesizzy.github.io/IzzyPortfolio)

## Overview

This is Izzy Piyale-Sheard's most comprehensive personal portfolio -- a dark-themed, panel-navigation single-page site that serves as a professional hub. It opens with a split-screen hero featuring a fading background image and rotating text describing Izzy as "a relationship builder, public speaker, negotiator, problem solver, continual learner, developer, designer, huge nerd, teacher, career coach, community builder, traveller." The site includes tabbed work experience sections (Work Experience, Side Projects, Public Speaking), a curated grid of 12+ side projects and blog posts, travel photography gallery, testimonials from colleagues, a "Featured In" section (Inc.com, TechNode, freeCodeCamp, Notable Life), and a Google Maps contact section centered on Toronto.

## Features

- Split-screen hero with image fader and text rotator animation
- Konami Code easter egg (Up Up Down Down Left Right Left Right B A) that triggers an animated modal with retro game sprites and music
- Panel-style navigation sidebar (Start, About, Experience, Portfolio, Contact)
- Tabbed work experience section: Work Experience, Side Projects, Public Speaking -- each with visual timeline
- Work history: LeafLogix, Lighthouse Labs, Hacker Paradise, University of Toronto
- 12+ side project showcases: COVID Survivors Project, Unlock China, Bitcoin to Tulips, freeCodeCamp Conference, The Collector Bitcoin, ClearCareer, Resume Website Builder, NomadKit, and more
- Public speaking timeline: Ryerson Tech Talks, Microsoft Store, ClearCareer workshops, Ryerson Hacks, U of T, and more
- "Featured In" logos section: Inc.com, TechNode, freeCodeCamp, Notable Life, The Lucky Few, DNX, Create Community
- Travel photography grid gallery with hover effects
- Testimonials section with expandable "view more" toggle
- Google Maps embedded contact section with "Write to me!" CTA
- Social links: Twitter, LinkedIn, Medium, GitHub, Instagram, YouTube
- Typed.js animated text in contact section
- Responsive design with dark/light scheme sections
- Page loader with SVG animation
- 72+ archived portfolio variants in the archive directory

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5
- CSS3 (Bootstrap 4, Animate.css, Themify Icons, Font Awesome, custom themes)
- jQuery
- Typed.js (typing animation)
- Simple Text Rotator (rotating hero text)
- Waypoints (scroll triggers)
- Images Loaded
- Google Maps JavaScript API
- Custom Konami Code script
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/IzzyPortfolio.git
   cd IzzyPortfolio
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `gh-pages` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/IzzyPortfolio`

## Project Structure

```
IzzyPortfolio/
├── index.html              # Main portfolio page
├── block.html              # Block layout variant
├── changelog.md            # Version changelog
├── CNAME                   # Custom domain config
├── nintendoworldcup-vsmatch.mp3  # Konami Code easter egg audio
├── assets/
│   ├── css/
│   │   ├── themes/theme-blue.min.css  # Main theme
│   │   ├── custom.css                 # Custom overrides
│   │   └── themify-icons.css          # Icon fonts
│   ├── js/
│   │   ├── core.js                    # Core application logic
│   │   ├── custom.js                  # Custom scripts
│   │   └── konami.js                  # Konami Code easter egg
│   ├── img/
│   │   ├── remote/                    # Travel photography
│   │   ├── blog/                      # Project thumbnails
│   │   ├── logos/                     # Company and feature logos
│   │   ├── headshots/                 # Testimonial photos
│   │   └── konami/                    # Retro game sprite GIFs
│   └── plugins/
│       ├── bootstrap/                 # Bootstrap 4
│       ├── font-awesome/              # Font Awesome
│       ├── typed.js/                  # Typed.js
│       ├── rotator/                   # Text rotator
│       └── waypoints/                 # Scroll waypoints
├── archive/                # 72+ archived portfolio variants
└── documentation/          # Theme documentation
```

## Tags

`portfolio`

## Created

2018-04

## Status

Active

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)

# Yggdrasil — Interactive 3D Norse Realm-Map Portfolio

An interactive 3D web portfolio built with Three.js, custom GLSL shaders, and Web Audio synthesis, mapping my academic journey, technical skills, projects, and honors across the realms of Yggdrasil.

Live Portfolio: https://kanak0091.github.io/Developer-portfolio/

## Overview

Instead of a traditional scrolling resume, this portfolio places visitors inside a procedural 3D cosmos centered around Yggdrasil (The World Tree). Seven celestial realms orbit the tree, each connected by pulsing Bifrost energy bridges and representing a distinct section of my profile:

- Midgard (About): Background, location, and academic summary
- Svartalfheim (Skills): Forged technical stack (Python, Bash, SQL, Git, REST APIs, Linux, Data Analytics)
- Muspelheim (Experience): Practical trials and hands-on engineering work
- Asgard (Projects): Featured repositories, data science capstone, and fraud detection engine
- Alfheim (Education): BCA in Artificial Intelligence & Data Science at K.R. Mangalam University
- Valhalla (Honors & Certifications): Technical certifications, industry workshops, hackathons, and Bharatanatyam distinction
- Bifrost (Contact): Direct links to Email, Phone, LinkedIn, and GitHub

## Key Features

- Procedural 3D World & Custom Shaders: Built with Three.js (r128), featuring custom GLSL vertex/fragment shaders for planetary surfaces, aurora sky domes, and animated Bifrost bridges, enhanced with UnrealBloomPass post-processing.
- Interactive Camera & Radar Mini-Map: Smooth spherical orbit controls (drag to orbit, scroll/pinch to zoom), automated camera flight to selected realms, raycasted hover states, and a synchronized bottom-left Rune Circle mini-map.
- Synthesized Ambient Audio: Built-in Web Audio API soundscape generating procedural low-frequency Nordic drones and filtered wind effects with zero external audio assets.
- Accessibility & Graceful Fallback: Includes a one-click Text View toggle for screen readers and keyboard navigation (Esc, ArrowLeft, ArrowRight, Enter), reduced-motion support, and automatic fallback if WebGL is unavailable.

## Tech Stack

- Core: HTML5, CSS3, Vanilla JavaScript (ES6+)
- 3D & Graphics: Three.js (r128), GLSL Shaders, EffectComposer / UnrealBloomPass
- Audio: Native Web Audio API
- Typography: Google Fonts (Cinzel & Inter)

## Project Structure

- index.html — Semantic structure, HUD overlays, preloader, and accessible reader view
- style.css — Dark Nordic theme, carved-stone panel styling, responsive breakpoints
- script.js — Resume data store, Three.js scene graph, shaders, camera physics & audio engine
- README.md — Project documentation

## Running Locally

1. Clone the repository:
   git clone https://github.com/Kanak0091/Developer-portfolio.git
2. Open index.html directly in any modern browser, or launch it with the Live Server extension in VS Code.

## Contact

Kanak Sachin Chaudhary
BCA in Artificial Intelligence & Data Science — K.R. Mangalam University, Gurugram

- Email: 2601060001@krmu.edu.in
- LinkedIn: https://linkedin.com/in/kanak-chaudhary-bbba52430
- GitHub: https://github.com/Kanak0091

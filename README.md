Anastasis Vlachatsis — Portfolio
Personal developer portfolio built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies — just a single file you can open in any browser or deploy anywhere in seconds.
Live Demo → (replace with your Vercel/GitHub Pages URL)

Features

Typing animation in the hero section cycling through roles
Floating terminal card displaying profile as JSON
Scroll fade-in animations on every section
Active nav highlight as you scroll through sections
Project cards with live/wip status badges and tech stack tags
Contact form with submit feedback
Fully responsive — mobile hamburger menu included
Dark theme with GitHub-inspired green accents, grid background, and glow effects


Sections
SectionDescriptionHeroName, typing tagline, terminal card, CTA buttonsAboutBio, education card, stats grid, interests snippetSkillsTag list by category + icon gridProjectsCards for all 4 projects with mockup previewsContactLinks + contact form



Zero dependencies — no npm, no build step
Google Fonts: Syne + DM Mono + DM Sans
CSS custom properties for theming
Vanilla JS for typing effect, scroll observer, and nav state


Getting Started
bashgit clone https://github.com/AnastasisVL/portfolio.git
cd portfolio
open index.html
That's it. No install, no build.

Deployment
Vercel
bashnpx vercel
GitHub Pages

Push to a repo named AnastasisVL.github.io
Go to Settings → Pages → Branch: main
Your site is live at https://anastasisvl.github.io

Netlify
Drag and drop the index.html file at app.netlify.com

Customization
All personal data is inline in the HTML. To update it:
WhatWhereName, tagline, bio#home and #about sectionsProjects.project-card blocks in #projectsSkills.skill-tag and .skill-card items in #skillsContact links.contact-link anchors in #contactTyping phrasesphrases array in the <script> tagColor schemeCSS variables in :root

License
MIT — free to use, fork, and adapt.

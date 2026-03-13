# Ehya Vue Frontend

This project is a port of the original Ehya static HTML/CSS site See [loneprog/Frontend-Class](https://github.com/loneprog/Frontend-Class.git) to a modern Vue 3 application using Vite and Tailwind CSS.

## Project Overview

Ehya is a frontend web app designed to help businesses grow faster by providing Instagram analytics and engagement tracking. The original design and layout are preserved, now implemented as reusable Vue components.

## Features

- Responsive navigation bar with dropdowns
- Hero section with business growth messaging
- Demo call-to-action and free trial button
- Sponsors section (Slack, Netflix, Google, Airbnb, Uber)
- Post analytics and graph visualization
- Hashtag tracking cards (growth, influencers, posts, location)
- Customer testimonials and brand growth highlights
- Footer with product, services, company, and more links
- Social media icons and copyright

## Tech Stack

- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Setup Instructions

1. **Install dependencies:**
	```bash
	npm install
	```
2. **Run development server:**
	```bash
	npm run dev
	```
3. **Build for production:**
	```bash
	npm run build
	```
4. **Preview production build:**
	```bash
	npm run preview
	```

## File Structure

- `src/` — Main source folder
  - `App.vue` — Root Vue component
  - `main.js` — App entry point
  - `style.css` — Global styles (Tailwind + custom)
  - `assets/` — Images and static assets
  - `components/` — Vue components (e.g., NavBar.vue)
- `index.html` — Vite entry HTML
- `package.json` — Project scripts and dependencies
- `tailwind.config.js` — Tailwind configuration
- `vite.config.js` — Vite configuration

## Credits

- Original design and layout from [loneprog/Frontend-Class](https://github.com/lonrprog/Frontend-Class.git)
- Image assets referenced in the original HTML (user must supply these in `src/assets/`)
- Fonts: [DM Sans](https://fonts.google.com/specimen/DM+Sans)

## License

This project is open source. See LICENSE for details.

## Contribution

Contributions are welcome! Please open issues or pull requests for improvements or bug fixes.

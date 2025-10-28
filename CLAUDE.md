# Project Overview

This project is a frontend SPA using vite, vue, daisyui and serve.

# Project Structure

- `src/assets`: static assets like images
- `src/components`: reusable vue components
- `src/pages`: vue pages
- `src/style.css`: global styles

# Styling Guidelines

- use daisyui classes for component styling
- Prioritize responsive design using mobile-first prefixes (e.g., `sm:`, `md:`, `lg:`)
- Global styles should be added to `src/style.css`, custom styles should be added to component's `<style>` block

# Development Notes

- When creating new components, follow the pattern established in `src/components/HelloWorld.vue` for code and interface separation
- Keep functions concise and single-purpose. If a function exceeds 42 lines or has multiple responsibilities, refactor it into smaller functions
- If a file exceeds 500 lines, split it into multiple files

# Available Commands

- `package.json` for a list of available npm scripts

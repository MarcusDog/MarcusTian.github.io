# Boki's Personal Blog

A digital-futuristic personal blog project built with HTML, CSS (Tailwind CSS), and JavaScript. Features include article creation, display, editing, particle effects, and more.

## Features

- Glassmorphism UI
- Particle background animation (powered by particles.js)
- Responsive design, mobile-friendly
- Markdown article editor (EasyMDE)
- Local storage for articles and drafts
- Category filtering and search
- Skills, projects, contact modules

## Project Structure

```
boki/
├── articles.html         # Article list page
├── editor.html           # Article editor page
├── index.html            # Home page
├── assets/
│   └── fonts/            # Font resources
├── css/
│   ├── animations.css    # Animation styles
│   └── style.css         # Global styles
├── js/
│   ├── articles.js       # Article list logic
│   ├── editor.js         # Editor logic
│   ├── main.js           # General interactions
│   └── particles-config.js # Particle background config & init
```

## Getting Started

1. Clone the repository locally
2. Use a local server (e.g. VSCode Live Server, http-server) to open `index.html`
3. Visit the homepage, articles list, and editor to experience all features

## Main Features

- **Home**: Personal info, skills, projects, latest articles, contact
- **Articles List**: Category filter, keyword search, pagination
- **Editor**: Markdown editing, tag management, icon selection, draft save & publish (data stored in browser localStorage)

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [particles.js](https://vincentgarreau.com/particles.js/)
- [EasyMDE](https://github.com/Ionaru/easy-markdown-editor) (editor only)

All dependencies are loaded via CDN, no extra installation required.

## Customization & Extension

- Styles can be adjusted in [`css/style.css`](css/style.css) and [`css/animations.css`](css/animations.css)
- Particle background config in [`js/particles-config.js`](js/particles-config.js)
- Article data structure and logic in [`js/editor.js`](js/editor.js) and [`js/articles.js`](js/articles.js)

## License

For learning and personal showcase only. Copyright © Boki.

---

Feedback and suggestions
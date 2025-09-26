# Search Project (CS50W)

This repository contains a lightweight front-end implementation of a search engine interface, inspired by the user experience of Google Search. The project was created as part of Harvard's CS50 Web Programming with Python and JavaScript course to demonstrate proficiency with semantic HTML, responsive layout techniques, and basic accessibility best practices.

## Features

- **Search landing page:** A minimalist home page (`index.html`) with a search bar, quick navigation buttons, and a responsive layout using modern CSS.
- **Image search mock-up:** An images-focused results page (`images.html`) with navigation links and styled search input elements.
- **Advanced search form:** A detailed advanced search form (`advanced.html`) that mimics Google's advanced search interface and showcases form semantics, inline labels, and alignment techniques.
- **Shared styling:** A single stylesheet (`style.css`) that provides consistent typography, spacing, and responsive behavior across the pages.
- **Night-mode:** The css adapts if the user as a prefered light or dark mode.

## Project Structure

```
.
├── advanced.html   # Advanced search form layout
├── images.html     # Image search mock-up
├── index.html      # Main search landing page
└── style.css       # Shared styles for all pages
```

## Getting Started

This project consists entirely of static assets. To explore the interface:

1. Clone the repository:
   ```bash
   git clone https://github.com/xavieralves16/search_project_cs50w.git
   cd search_project_cs50w
   ```
2. Open `index.html` in your preferred browser. You can double-click the file or serve the directory through a simple HTTP server such as:
   ```bash
   python3 -m http.server
   ```
   Then navigate to `http://localhost:8000/` in your browser.

No build tooling or package installation is required.


## Accessibility & Browser Support

The markup uses semantic HTML elements, descriptive labels, and accessible form controls to provide a usable experience with keyboard navigation. The layout relies on standard CSS properties and should render correctly in all modern browsers.

## License

This project is provided for educational purposes as part of the CS50W coursework. No specific license has been applied; feel free to adapt it for personal learning projects.
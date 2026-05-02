# GigaTECH Website

This project is a static website for GigaTECH, featuring multiple pages and modern UI components. The site is built using HTML, CSS (including Bootstrap and custom styles), JavaScript, and several third-party libraries for enhanced interactivity and design.

## Project Structure

- **index.html**: Main landing page
- **about.html, contact.html, project.html, service.html, team.html, testimonial.html, 404.html**: Additional site pages
- **css/**: Contains Bootstrap and custom stylesheets
- **js/main.js**: Main JavaScript file for custom scripts
- **img/**: Image assets
- **lib/**: Third-party libraries and plugins
  - **animate/**: Animation CSS
  - **counterup/**: Counter animation JS
  - **easing/**: Easing functions for animations
  - **isotope/**: Filtering and sorting layouts
  - **lightbox/**: Image lightbox plugin (with its own css, js, images)
  - **owlcarousel/**: Carousel/slider plugin (with assets)
  - **waypoints/**: Scroll-based triggers
  - **wow/**: Reveal animations on scroll
- **scss/**: SCSS source files for Bootstrap and custom styles

## How to Use

1. Open `index.html` in your browser to view the homepage.
2. Navigate to other pages using the menu or by opening their respective HTML files.
3. All styles and scripts are loaded locally from the `css/`, `js/`, and `lib/` folders.

## Customization

- Edit SCSS files in `scss/` for advanced style changes. Compile to CSS as needed.
- Add or replace images in the `img/` folder.
- Update or add JavaScript in `js/main.js` for custom functionality.

## Libraries & Dependencies

- Bootstrap (CSS framework)
- Animate.css, WOW.js (animations)
- CounterUp, Waypoints (counters)
- Isotope (filtering/sorting)
- Lightbox (image modals)
- Owl Carousel (sliders)
- Easing (animation easing)

All dependencies are included locally in the `lib/` directory.

## Notes

- No build tools or package managers are required; all files are static and self-contained.
- For SCSS changes, use a tool like [Sass](https://sass-lang.com/) to compile `.scss` to `.css`.
- The project is ready to deploy on any static web server.

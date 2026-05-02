# DIJIT PROGRAM - Job Board Bootstrap 5 Template

DIJIT PROGRAM is a high-quality, production-ready Job Board HTML5 template designed for creating modern job listing websites. It features a clean, responsive layout built on Bootstrap 5 and vanilla JavaScript/jQuery.

## Project Structure

The project follows a standard static multi-page application (MPA) structure:

```text
.
├── *.html                  # Individual pages (index, about, contact, etc.)
└── assets/                 # Static assets
    ├── css/                # Stylesheets
    │   ├── plugins/        # CSS for third-party plugins
    │   ├── vendor/         # Core frameworks (Bootstrap, etc.)
    │   └── style.css       # Main custom theme styles
    ├── fonts/              # Icon fonts and typography
    ├── images/             # All project images and logos
    └── js/                 # JavaScript files
        ├── plugins/        # JS for third-party plugins
        ├── vendor/         # Core libraries (jQuery, Bootstrap, Modernizr)
        └── main.js         # Main custom logic and plugin initialization
```

## Technology Stack

- **Core**: HTML5, CSS3, JavaScript
- **CSS Framework**: [Bootstrap 5](https://getbootstrap.com/)
- **JavaScript Library**: [jQuery 3.5.0](https://jquery.com/)
- **Icons**: [LinearIcons](https://linearicons.com/), [FontAwesome](https://fontawesome.com/)
- **Utilities**: [Modernizr 3.10.0](https://modernizr.com/)

## Architecture Highlights

1. **Multi-Page Layout**: Each HTML file represents a distinct page. Headers and footers are replicated across files to ensure a standalone experience for each page without a backend.
2. **Responsive Design**: Utilizes Bootstrap's grid system and utility classes for seamless performance across mobile, tablet, and desktop devices.
3. **Plugin-Driven Interactivity**:
    - **Slick Slider**: Used for carousels and testimonial sections.
    - **Nice Select**: Enhances standard `<select>` elements with a customizable UI.
    - **Magnific Popup**: For image lightboxes and video popups.
4. **Theming**: A robust `style.css` file handles global variables and component-specific styling, allowing for easy customization of colors and typography.

## How to Use

1. **Local Development**: Simply open `index.html` in any modern web browser.
2. **Customization**:
    - Edit HTML files to change content and structure.
    - Modify `assets/css/style.css` to update visual styles.
    - Update `assets/js/main.js` to change interactivity or plugin settings.
3. **Deployment**: Upload the entire directory to any static web hosting provider (e.g., GitHub Pages, Netlify, Vercel).

---
*Created by Antigravity AI*

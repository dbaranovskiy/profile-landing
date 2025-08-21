# System Patterns

## System Architecture:
The "Handy Dandy" project follows a simple, client-side architecture. It is a static website composed of HTML, CSS, and JavaScript files, designed for direct deployment on a web server or CDN. There is no backend component or database.

## Key Technical Decisions:
- **Static Site:** Chosen for simplicity, performance, and ease of deployment. No server-side processing is required.
- **Vanilla HTML, CSS, JavaScript:** Avoids complex frameworks or libraries for minimal overhead and maximum compatibility. This also makes the project lightweight and easy to maintain.
- **Responsive Design:** Utilizes CSS media queries and flexible layouts to ensure optimal viewing across various devices.

## Design Patterns in Use:
- **Modular CSS:** CSS is organized into logical sections (e.g., `style.css` for general styling).
- **Separation of Concerns:** HTML for structure, CSS for presentation, and JavaScript for interactivity are kept in separate files.

## Component Relationships:
- `index.html`: The main entry point, containing the header (hero section), "Our Story" (about), "Our Services" (services grid), and "Get In Touch" (contact) sections. It links to CSS and JavaScript files.
- `css/style.css`: Contains all global styles, responsive design rules, and styling for specific sections and components like service cards and navigation.
- `js/main.js`: Handles any interactive elements or dynamic content loading (currently minimal, primarily for navigation).
- `assets/`: Directory for images (e.g., the handyman image in the "Our Story" section), fonts, and other media.

## Critical Implementation Paths:
- **Navigation:** The bottom navigation menu (`.bottom-nav`) provides smooth scrolling links to `#home`, `#about`, `#services`, and `#contact` sections.
- **Call to Action:** The "Get a Free Estimate" button in the hero section links to the `#contact` section.
- **Service Display:** The `.services-grid` effectively showcases various handyman services using `.service-card` elements with icons and descriptions.
- **Contact Information:** The `#contact` section clearly presents phone and email contact details.

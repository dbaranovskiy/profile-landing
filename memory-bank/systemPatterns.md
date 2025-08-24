# System Patterns

## System Architecture:
The "Handy Dandy" project follows a simple, client-side architecture. It is a static website composed of HTML, Tailwind CSS, and Alpine.js, designed for direct deployment on a web server or CDN. There is no backend component or database.

## Key Technical Decisions:
- **Static Site:** Chosen for simplicity, performance, and ease of deployment. No server-side processing is required.
- **Tailwind CSS:** Utilized for a utility-first CSS approach, enabling rapid UI development and consistent styling.
- **Alpine.js:** Integrated for lightweight, declarative JavaScript behavior directly within the HTML, minimizing the need for a separate `main.js` file for simple interactivity.
- **Responsive Design:** Achieved through Tailwind's responsive utilities and flexible layouts to ensure optimal viewing across various devices.

## Design Patterns in Use:
- **Utility-First CSS:** Leveraging Tailwind CSS classes directly in HTML for styling.
- **Declarative JavaScript:** Using Alpine.js for component-like behavior with minimal boilerplate.
- **Separation of Concerns (Modified):** While HTML, CSS, and JS are conceptually separate, Tailwind and Alpine integrate styling and behavior directly into the HTML for efficiency.

## Component Relationships:
- `index.html`: The main entry point, containing the header (hero section), "Services" (services grid), "Projects", "Testimonials", and "Contact Form" sections. It links to Tailwind CSS and Alpine.js CDNs.
- **Inline Styles/Scripts:** Tailwind CSS classes and Alpine.js directives are applied directly within `index.html`.
- `assets/`: Directory for images (e.g., the hero section background image, project images, testimonial avatars), favicon, and other media.

## Critical Implementation Paths:
- **Navigation:** The main navigation and mobile menu provide smooth scrolling links to `#services`, `#projects`, `#testimonials`, and `#contact-form` sections.
- **Call to Action:** The "Book Now" button in the header and "Book a Consultation" button in the hero section link to the `#contact-form` section.
- **Service Display:** The services section (`#services`) effectively showcases various handyman services using `.service-card` elements with SVG icons and descriptions.
- **Project Showcase:** The projects section (`#projects`) displays various completed works with images and descriptions.
- **Testimonials:** The testimonials section (`#testimonials`) presents customer reviews.
- **Contact Form:** The `#contact-form` section provides a form for users to request estimates.

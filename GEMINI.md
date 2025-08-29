
# Project Overview

This project is a single-page landing page for a fictional handyman business called "Handy Dandy". It's designed to showcase the business's services, projects, and customer testimonials, and to provide a clear call-to-action for potential customers to request a free estimate.

**Key Technologies:**

*   **HTML:** The core markup for the page structure.
*   **Tailwind CSS:** A utility-first CSS framework for styling the page. The project uses the Tailwind CSS CDN.
*   **Alpine.js:** A minimal JavaScript framework for adding interactivity to the page, such as the mobile menu. The project uses the Alpine.js CDN.
*   **Schema.org:** The page includes structured data (JSON-LD) to improve search engine visibility.

**Architecture:**

The project consists of a single `index.html` file that contains all the HTML, CSS, and JavaScript. The CSS and JavaScript are included via CDNs. The images are hosted on Google's servers.

# Building and Running

This is a static website, so there is no build process. To run the project, simply open the `index.html` file in a web browser.

# Development Conventions

*   **Styling:** The project uses Tailwind CSS for styling. All styles are applied directly in the HTML using utility classes.
*   **JavaScript:** The project uses Alpine.js for interactivity. All JavaScript is written directly in the HTML using `x-data`, `x-show`, etc.
*   **Images:** The project uses images hosted on Google's servers.
*   **SEO:** The project includes a `robots.txt` file and a `sitemap.xml` file to improve search engine optimization. The `index.html` file also includes a canonical URL and structured data (JSON-LD).

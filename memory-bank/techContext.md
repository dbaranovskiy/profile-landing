# Tech Context

## Technologies Used:
- **HTML5:** For structuring the content of the web page (`index.html`).
- **CSS3:** For styling the web page, including layout, colors, typography, and responsiveness (`css/style.css`).
- **JavaScript (ES6+):** For any interactive elements or dynamic content manipulation (`js/main.js`). Currently, this file appears to be minimal, primarily handling navigation.

## Development Setup:
- **Text Editor:** VS Code (as indicated by the environment details).
- **Browser:** Any modern web browser for testing and viewing the site.
- **Local Server:** The project is typically served locally using the VS Code Live Server extension at `http://127.0.0.1:5500/`. This URL should be used for checking changes during development.

## Technical Constraints:
- **No Backend:** The project is purely client-side. Any dynamic features (like contact forms) must rely on third-party services.
- **Browser Compatibility:** Design should aim for broad compatibility with modern browsers.
- **Performance:** Keep file sizes minimal (images optimized, CSS/JS minified if deployed) to ensure fast loading times.

## Dependencies:
- **External Libraries:** The project currently uses SVG icons embedded directly in the HTML for navigation and service cards. It does not appear to use external JavaScript libraries (like jQuery, React, Vue) or CSS frameworks (like Bootstrap, Tailwind CSS).
- **Fonts/Icons (Potential):** If custom fonts (e.g., Google Fonts) or external icon libraries (e.g., Font Awesome) were to be used, they would be external dependencies loaded via CDN or self-hosted. Currently, the SVG icons are inline.

## Tool Usage Patterns:
- **File System Operations:** `mkdir`, `write_to_file`, `read_file`, `list_files` for managing project structure and content.
- **Browser Interaction:** `browser_action` for testing and verifying the live appearance and functionality of the page.
- **Command Execution:** `execute_command` for running local development servers or build scripts if they become necessary.

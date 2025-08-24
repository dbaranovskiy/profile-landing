# Tech Context

## Technologies Used:
- **HTML5:** For structuring the content of the web page (`index.html`).
- **Tailwind CSS:** For styling the web page, including layout, colors, typography, and responsiveness. Loaded via CDN.
- **Alpine.js:** For adding declarative JavaScript behavior to HTML. Loaded via CDN.
- **JavaScript (ES6+):** For any custom interactive elements or dynamic content manipulation.

## Development Setup:
- **Text Editor:** VS Code (as indicated by the environment details).
- **Browser:** Any modern web browser for testing and viewing the site.
- **Local Server:** The project is typically served locally using the VS Code Live Server extension at `http://127.0.0.1:5500/`. This URL should be used for checking changes during development.

## Technical Constraints:
- **No Backend:** The project is purely client-side. Any dynamic features (like contact forms) must rely on third-party services.
- **Browser Compatibility:** Design should aim for broad compatibility with modern browsers.
- **Performance:** Keep file sizes minimal (images optimized, CSS/JS minified if deployed) to ensure fast loading times.

## Dependencies:
- **Tailwind CSS CDN:** For utility-first CSS styling.
- **Alpine.js CDN:** For lightweight JavaScript interactivity.
- **Google Fonts:** "Plus Jakarta Sans" is loaded for typography.
- **SVG Icons:** Embedded directly in the HTML for navigation and service cards.

## Tool Usage Patterns:
- **File System Operations:** `mkdir`, `write_to_file`, `read_file`, `list_files` for managing project structure and content.
- **Browser Interaction:** `browser_action` for testing and verifying the live appearance and functionality of the page.
- **Command Execution:** `execute_command` for running local development servers or build scripts if they become necessary.

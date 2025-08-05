# System Patterns

The project uses a simple static site architecture, well-suited for a content-focused website.

## Architecture

- **Static Site:** The entire website is composed of static files (HTML, CSS, JSON), ensuring fast load times and simple hosting. There is no server-side logic or database.
- **Content Hub Model:** The `index.html` acts as a central hub or table of contents. It links out to individual article guides located in the `sharing/` directory.
- **Data-driven Content:** `pages.json` is used to populate the list of articles on the main page, creating a separation between data and presentation.
- **Centralized Styling:** All styles are located in a single `style.css` file, ensuring a consistent look and feel across all pages.

# System Logic

The application follows the Astro file-based routing architecture and primarily relies on Static Site Generation (SSG) for performance.

## Routing and Views
- **`src/pages/`**: Contains all the application routes. Each `.astro` or `.md` file corresponds to a specific URL path.
- **`src/layouts/`**: Houses layout templates that wrap page content, ensuring consistent headers, footers, and metadata across the site.

## Data Management
- Data fetching occurs at the component level during the build process.
- For dynamic content requirements in the future, the project may implement Server-Side Rendering (SSR) via Astro's hybrid rendering configuration.

## Assets
- **`public/`**: Stores static assets (images, fonts, raw files) that do not require processing by the build pipeline. These are served directly at the root path.

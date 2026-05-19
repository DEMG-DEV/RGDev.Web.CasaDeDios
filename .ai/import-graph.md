# Import Graph

The general flow of dependencies and imports within the application:

1. **Routing Entry Points**:
   `src/pages/index.astro` (and other pages) act as the primary entry points.

2. **Layout Wrappers**:
   Pages import and utilize layout components from `src/layouts/` (e.g., `src/layouts/Layout.astro`) to structure the HTML document and common UI elements.

3. **UI Components**:
   Pages and Layouts import functional and visual UI elements from `src/components/`.

4. **Styles & Assets**:
   Global styles (if any) are typically imported within the base layout.
   Static assets (images, icons) can be referenced directly from the `public/` directory or imported if they reside in `src/assets/`.

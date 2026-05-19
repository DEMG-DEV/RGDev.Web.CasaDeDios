# Rules

1. **Architecture**: Follow Astro best practices. Use file-based routing strictly within the `src/pages/` directory.
2. **Components**: Build reusable UI elements using Astro components (`.astro`) in `src/components/`. If complex client-side interactivity is required, use framework components (e.g., React/Svelte) but leverage Astro's Islands architecture to minimize JavaScript payload.
3. **Styling**: Ensure responsive, mobile-first design. Use modern styling approaches (like Tailwind CSS if integrated, or vanilla CSS with scoped styles).
4. **Performance**: Maximize static site generation (SSG) where possible. Keep client-side scripting to an absolute minimum.
5. **Language & i18n**: The primary content language is Spanish. Structure text content to be easily adaptable for future internationalization (i18n) if needed.
6. **Code Quality**: Write typed (TypeScript), clean, and self-documenting code. Do not leave placeholder text or console logs in production code.

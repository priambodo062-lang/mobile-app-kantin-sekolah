# Project architecture

KantinKita uses TanStack Start with React and TypeScript. The index route in `src/routes/index.tsx` contains the responsive canteen prototype and its screen transitions. `src/routes/__root.tsx` owns the document language and sharing metadata. `src/styles.css` defines the orange, cream, and warm-neutral design system and responsive layouts. `netlify.toml` configures hosting and the remote image allowlist.

Keep all customer-facing text in Indonesian. Use Lucide icons and the existing CSS classes. The desktop sidebar becomes a fixed bottom navigation below 700px. Maintain sufficient space above the mobile navigation for the floating cart.

The product is currently a frontend demo: React state stores cart, favorites, notes, and simulated order status for the current page session only. The order confirmation explicitly identifies the simulation. Do not imply real payments or fulfillment. Future persistent records must use Netlify Database, and account authentication must use Netlify Identity.

Remote food photographs must pass through Netlify Image CDN. No build artifacts should be committed. The deployment pipeline performs build validation.

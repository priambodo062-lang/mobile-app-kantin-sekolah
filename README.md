# KantinKita

A responsive Indonesian campus canteen ordering prototype inspired by the supplied mobile reference. Browse stalls and food, search and filter menus, save favorites, customize portions, review a cart, and explore order tracking and pickup tickets.

Built with React, TypeScript, TanStack Start, Lucide icons, and CSS. Food photography uses Netlify Image CDN.

## Local development

Install dependencies with `pnpm install`, then run `netlify dev --port 8889`.

This is an interactive frontend prototype. Cart, favorites, and simulated orders use React state and reset on refresh. It does not send orders to a real canteen, process payments, or create user accounts. Payment in the prototype is collected at the stall.

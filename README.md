# Financial Operations

A modern SaaS landing page for a **financial-operations platform** ("Financial operations for growth businesses"), built with **React, Vite, TypeScript, Tailwind CSS and shadcn/ui**. Includes an interactive task-board demo, marketing sections (hero, features, testimonials, pricing, footer) and a polished cosmic-themed design.

## Features

- **Marketing landing page** — hero, features, testimonials, pricing and footer sections with a cosmic/gradient design language
- **Interactive task board demo** — draggable task columns and cards showcasing product capability
- **Payment automation story** — automated payment workflows, approval chains, recurring payments, invoice processing
- **Real-time analytics story** — dashboards for cash flow, payment volumes, transaction success rates
- **Risk management story** — fraud detection and transaction monitoring narrative
- **Dark cosmic theme** with animated particle/grid background and glow effects
- **Fully responsive** mobile-first layout
- **shadcn/ui components** — accordion, dialog, toast, tooltip, command palette and more

## Tech Stack

- [React 18](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- [Vite 5](https://vite.dev/) — dev server and build tool
- [Tailwind CSS 3](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
- [React Router](https://reactrouter.com/) — client-side routing (with 404 fallback page)
- [TanStack Query](https://tanstack.com/query) — data fetching
- [Lucide](https://lucide.dev/) icons, Recharts, react-hook-form + zod

## Quick Start

Prerequisites: [Node.js](https://nodejs.org/) 18+ and npm.

```bash
# Clone the repository
git clone https://github.com/girishlade111/Financial-operations.git
cd Financial-operations

# Install dependencies
npm install --legacy-peer-deps

# Start the dev server
npm run dev
```

Open http://localhost:8080 in your browser.

## Project Structure

```
Financial-operations/
├── public/                  # Static assets
├── src/
│   ├── components/          # Page sections (Header, HeroSection, Features,
│   │                        # Testimonials, Pricing, Footer, TaskBoard, Logo)
│   │   └── ui/              # shadcn/ui primitives
│   ├── pages/               # Route pages (Index, NotFound)
│   ├── hooks/               # Custom React hooks
│   ├── lib/                 # Utility helpers
│   ├── App.tsx              # Router + providers
│   ├── main.tsx             # Entry point
│   └── index.css            # Tailwind + theme tokens
├── index.html               # HTML shell
└── vite.config.ts           # Vite configuration
```

## Build & Deploy

```bash
npm run build        # Produces the static site in dist/
```

The output in `dist/` is fully static and can be hosted on any static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel). A `public/_redirects` file maps `/*` to `/index.html` for client-side routing.

## Environment Variables

None required — the site is fully client-side with no backend or API keys.

## License

This project is open source under the MIT License.

---

## 👨‍💻 Built by Girish Lade

**Financial Operations** is an open-source project by [Girish Lade](https://github.com/girishlade111).

Check out more projects at [ladestack.in](https://ladestack.in).

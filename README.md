# Muhammed Tallat Hassan — Portfolio
An interactive portfolio site for **Muhammed Tallat Hassan** — Back End .NET Developer & AI / Data Science enthusiast based in Egypt.
Built with TanStack Start, React 19, Tailwind CSS v4, and an interactive 3D hero scene powered by react-three-fiber.
🌐 **Live portfolio:** https://mhmdtallat-portfolio.web.app/
---
## ✨ Features
- **Interactive 3D model** — animated torus knot with distort material, hover/click reactions, auto-rotate and drag controls (react-three-fiber + drei)
- **Animated UI** — fade-in/fade-up entrances, glowing CTA, marquee tech-stack ribbon, hover-lift cards
- **Custom design system** — dark neon theme defined fully via `oklch` semantic tokens in `src/styles.css`
- **Sections** — Hero, About, Tech Stack, Pinned Projects, Contact
- **SEO ready** — per-route `<head>` metadata, semantic HTML, responsive layout
## 🧰 Tech Stack
| Layer       | Tools |
|-------------|-------|
| Framework   | TanStack Start v1, React 19, Vite 7 |
| Styling     | Tailwind CSS v4, shadcn/ui, Lucide icons |
| 3D / Motion | three, @react-three/fiber, @react-three/drei |
| Language    | TypeScript (strict) |
## 🚀 Getting Started
```bash
# install dependencies
bun install
# start the dev server
bun run dev
# production build
bun run build
```
The app runs at `http://localhost:5173` by default.
## 📁 Project Structure
```
src/
├── components/
│   ├── HeroScene.tsx        # Interactive 3D hero (R3F)
│   └── ui/                  # shadcn/ui primitives
├── routes/
│   ├── __root.tsx           # Root layout + HTML shell
│   └── index.tsx            # Portfolio landing page
├── styles.css               # Design system tokens & animations
└── router.tsx               # TanStack Router setup
```
## 🎨 Customizing
- **Colors / animations** — edit tokens in `src/styles.css` (`:root` block + `@theme inline` keyframes)
- **Content** — update arrays in `src/routes/index.tsx` (`socials`, `stacks`, `projects`, `marqueeTags`)
- **3D model** — tweak geometry, material, or interaction in `src/components/HeroScene.tsx`
## 🔗 Connect
- 🌐 [Portfolio](https://mhmdtallat-portfolio.web.app/)
- 💼 [LinkedIn](https://www.linkedin.com/in/muhammed-tallat-a440881b7)
- 🐦 [X / Twitter](https://twitter.com/MHMD_TAL3AT)
- 👤 [Facebook](https://www.facebook.com/mohamed.Tallat.104203)
---
Made with care · © Muhammed Tallat Hassan

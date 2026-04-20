# E. HUNTER | Digital Designer Portfolio

A **modern, animated portfolio website** built with **Next.js 16**, **React 19**, and **Tailwind CSS v4**. Features smooth animations, custom cursor, noise overlay, and a sleek dark-themed design.

---

## 🚀 Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | Next.js 16.2.3 |
| **Language** | TypeScript 5 |
| **UI Library** | React 19.2.4 |
| **Styling** | Tailwind CSS v4 |
| **Animations** | Framer Motion 12.38.0 |
| **Smooth Scroll** | Lenis 1.3.23 |
| **Icons** | Lucide React 1.8.0 |
| **Fonts** | Geist (Next.js Google Font) |
| **Build Tool** | ESLint 9 |

---

## ✨ Features

- **Hero Section** — Bold typography animations with staggered reveals
- **Case Studies** — Showcase of design projects with hover effects
- **Services** — Professional services offered section
- **Smooth Scrolling** — Powered by **Lenis** for buttery-smooth scroll experience
- **Custom Cursor** — Interactive cursor that follows mouse movement
- **Noise Overlay** — Subtle grain/texture effect for visual depth
- **Responsive Design** — Fully responsive on all devices
- **Dark Theme** — Sleek pure black background (#000000)
- **Framer Motion** — Advanced entrance and hover animations
- **Type Safety** — Full TypeScript support

---

## 📦 Project Structure

```
portfolio4/
├── src/
│   ├── app/
│   │   ├── globals.css      # Global Tailwind styles
│   │   ├── layout.tsx     # Root layout with fonts & providers
│   │   └── page.tsx       # Main homepage
│   ├── components/
│   │   ├── Hero.tsx           # Hero section
│   │   ├── CaseStudies.tsx    # Portfolio/projects section
│   │   ├── Services.tsx       # Services offered
│   │   ├── Navbar.tsx         # Navigation bar
│   │   ├── Footer.tsx         # Footer section
│   │   ├── SmoothScroll.tsx  # Lenis scroll provider
│   │   ├── CustomCursor.tsx  # Custom cursor component
│   │   └── NoiseOverlay.tsx # Grain texture overlay
│   └── lib/                   # Utility functions
├── public/                    # Static assets
├── tailwind.config.ts     # Tailwind configuration
├── next.config.ts       # Next.js configuration
├── tsconfig.json         # TypeScript configuration
├── package.json         # Dependencies
└── README.md            # This file
```

---

## 🛠️ Configuration

### Tailwind CSS (`tailwind.config.ts`)

- **Custom Colors**: `pure-black` (#000000), `pure-white` (#FFFFFF)
- **Fonts**: Geist Sans (variable), Grotesk
- **Content Paths**: Scans `./src/app/**` and `./src/components/**`

### TypeScript (`tsconfig.json`)

- **Target**: ES2017
- **Strict Mode**: Enabled
- **Path Alias**: `@/*` maps to `./src/*`
- **JSX**: react-jsx

### Next.js (`next.config.ts`)

- Minimal config (currently empty, ready for custom extensions)

---

## 📋 Getting Started

### Prerequisites

- Node.js 18+ 
- npm / yarn / pnpm / bun

### Installation

```bash
# Clone the repository
git clone https://github.com/girishlade111/digital-designer-portfolio.git
cd digital-designer-portfolio

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### Development Server

```bash
# Start development server
npm run dev

# Open in browser
http://localhost:3000
```

### Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server |
| `npm run build` | Production build |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint |

---

## 🏗️ Build & Deploy

### Build for Production

```bash
npm run build
```

### Deploy on Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

**Or** connect your GitHub repo to Vercel for automatic deployments.

---

## 📊 Stats

- **Lines of Code**: ~500+ (including components)
- **Dependencies**: 14 packages
- **Components**: 8 reusable components
- **Font**: Geist (9 weights)
- **Animations**: 15+ motion variants

---

## 🎨 Customization

### Changing Colors

Edit `tailwind.config.ts`:

```typescript
theme: {
  extend: {
    colors: {
      'pure-black': '#000000',
      'pure-white': '#FFFFFF',
      // Add your custom colors
    },
  },
},
```

### Adding Fonts

Edit `src/app/layout.tsx`:

```typescript
import { YourFont } from 'next/font/google';

const yourFont = YourFont({
  variable: '--font-your-font',
  subsets: ['latin'],
  weight: ['400', '700'],
});
```

### Adding Components

1. Create component in `src/components/`
2. Import in `src/app/page.tsx` or layout
3. Use with Tailwind classes

---

## 📄 License

MIT License — Feel free to use this portfolio as a template for your own projects.

---

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS](https://tailwindcss.com)
- [Framer Motion](https://www.framer.com/motion/)
- [Lenis](https://lenis.studio/)
- [Lucide Icons](https://lucide.dev/)

---

**Built with ❤️ using Next.js 16 & React 19**
# Taha Asghar — Personal Portfolio

A modern, dark-themed personal portfolio for **Taha Asghar**, Warehouse & Logistics Professional at Tamer Logistics, Jeddah, Saudi Arabia. Built with Next.js 16, React 19, Tailwind CSS v4, and Framer Motion.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 16.2 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS v4 |
| Animations | Framer Motion 12 |
| Icons | React Icons v5 |
| Font | Geist (via `next/font/google`) |
| Deployment | Vercel |

---

## Features

- **Dark theme** — pure black background with `#2CFF05` neon green accent
- **Typewriter hero** — cycles through 4 professional titles
- **Char-by-char name animation** — blur + slide-up on page load
- **Scroll-triggered animations** — every section animates in *and* out (bi-directional)
- **Animated word/text reveals** — `AnimatedText` component for all headings
- **Infinite tech stack marquee** — two rows scrolling in opposite directions, pauses on hover
- **Vertical timeline** — experience section with animated line draw
- **Animated skill bars** — progress bars fill on scroll-in
- **Fully responsive** — mobile-first, works on all screen sizes
- **Custom scrollbar** — neon green accent

---

## Sections

1. **Hero** — Name, typewriter title, CTA buttons, stats
2. **About** — Summary, contact info cards, Employee of the Year badge
3. **Skills** — Three category cards (Warehouse & Ops, Technology & Data, Compliance & Leadership)
4. **Tech Stack** — Infinite marquee with 16 tools: Oracle ERP, SAP, Power BI, Excel, and more
5. **Experience** — Timeline: Tamer Logistics (Jan 2024–Present) + The Game Company internship
6. **Education & Certifications** — Degree, 3 certifications, 2 awards, proficiency bars
7. **Contact** — Email / Phone / Location cards, Gmail CTA

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install & Run

```bash
# Clone the repo
git clone https://github.com/ibtiwahab/Taha-portfolio.git
cd taha-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm run start
```

---

## Project Structure

```
taha-portfolio/
├── app/
│   ├── components/
│   │   ├── AnimatedText.tsx   # Reusable word-by-word text animation
│   │   ├── Navbar.tsx         # Fixed navbar with scroll effect
│   │   ├── Hero.tsx           # Full-screen hero section
│   │   ├── About.tsx          # About / summary section
│   │   ├── Skills.tsx         # Core skills category cards
│   │   ├── TechStack.tsx      # Infinite scrolling tech marquee
│   │   ├── Experience.tsx     # Work experience timeline
│   │   ├── EducationCerts.tsx # Education, certs, awards, skill bars
│   │   ├── Contact.tsx        # Contact cards + Gmail CTA
│   │   └── Footer.tsx         # Footer with nav links
│   ├── globals.css            # CSS variables, Tailwind config, keyframes
│   ├── layout.tsx             # Root layout + SEO metadata
│   └── page.tsx               # Page composition
├── public/                    # Static assets
├── package.json
└── README.md
```

---

## Customisation

All personal data lives directly in each component — no separate data files needed. To update:

| What | File |
|------|------|
| Name, title, description | `Hero.tsx` |
| Summary, contact info | `About.tsx` |
| Skill categories | `Skills.tsx` |
| Tech stack marquee items | `TechStack.tsx` |
| Job history | `Experience.tsx` |
| Degree, certs, awards | `EducationCerts.tsx` |
| Contact links | `Contact.tsx` |
| SEO title & description | `layout.tsx` |
| Colors & design tokens | `globals.css` |

---

## Color Palette

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | `#000000` | Page background |
| `--bg-card` | `#080808` | Card backgrounds |
| `--accent` | `#2CFF05` | Primary accent (neon green) |
| `--text` | `#ffffff` | Primary text |
| `--text-muted` | `#999999` | Secondary text |

---

## Deployment

The easiest way to deploy is via [Vercel](https://vercel.com):

1. Push this repo to GitHub
2. Import the project at [vercel.com/new](https://vercel.com/new)
3. Vercel auto-detects Next.js — click **Deploy**

---

## License

This project is for personal use. Feel free to use it as a template — attribution appreciated.

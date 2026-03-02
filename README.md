# StampID

A modern web application built with [Next.js](https://nextjs.org) 16, React 19, TypeScript, and Tailwind CSS 4.

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org) 16 (App Router)
- **Language:** TypeScript 5
- **UI:** React 19
- **Styling:** Tailwind CSS 4
- **Font:** [Geist](https://vercel.com/font) (Sans & Mono)
- **Linting:** ESLint 9

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) 18.17 or later
- npm, yarn, pnpm, or bun

### Installation

```bash
git clone https://github.com/malbovado/stampid.git
cd stampid
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

The page auto-updates as you edit files in the `app/` directory. Start by modifying `app/page.tsx`.

### Build & Production

```bash
# Create an optimized production build
npm run build

# Start the production server
npm run start
```

### Linting

```bash
npm run lint
```

## Project Structure

```
stampid/
├── app/
│   ├── favicon.ico       # App favicon
│   ├── globals.css        # Global styles (Tailwind)
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── public/                # Static assets
├── eslint.config.mjs      # ESLint configuration
├── next.config.ts         # Next.js configuration
├── postcss.config.mjs     # PostCSS configuration
├── tailwind.config.*      # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
└── package.json
```

## Deployment

The easiest way to deploy is with [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme)

For other deployment options, see the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

## Learn More

- [Next.js Documentation](https://nextjs.org/docs) — features and API reference
- [Learn Next.js](https://nextjs.org/learn) — interactive tutorial
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) — utility-first CSS framework

## License

This project is private.

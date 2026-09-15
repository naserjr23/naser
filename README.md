# naser

A Next.js application with Vercel Speed Insights integration.

## Features

- ⚡️ Next.js 16.3.5 with App Router
- 📊 Vercel Speed Insights for performance monitoring
- 🎨 TypeScript support
- 💅 ESLint configured

## Getting Started

First, install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Speed Insights

This project is configured with [Vercel Speed Insights](https://vercel.com/docs/speed-insights) to automatically track Core Web Vitals and performance metrics.

The `<SpeedInsights />` component is integrated in `app/layout.tsx` and will start collecting data once the application is deployed to Vercel.

## Build

Build the production application:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
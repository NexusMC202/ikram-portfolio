# IKRAM — Creative Developer Portfolio

An interactive personal portfolio for Ikram, focused on creative development, frontend engineering, 3D web, AI, games, and experimental systems.

## Overview

The site presents Ikram's work as a cinematic, editorial experience rather than a conventional portfolio. DOM content carries information while a procedural Three.js Core supplies atmosphere, depth, and motion.

## Features

- Interactive procedural Three.js Core with React Three Fiber
- Lenis smooth scrolling with reduced-motion support
- Responsive hero, work, playground, toolkit, process, journey, philosophy, and contact sections
- Case-study routes for ForceCore, Nexus Sky, and ForceCore AI
- Core Terminal easter egg with project and navigation commands
- Index overlay for fast recruiter-friendly navigation
- `?lite=1` low-power mode
- WebGL error fallback that preserves the DOM experience
- Responsive mobile navigation and desktop custom cursor
- Accessible labels, semantic headings, and keyboard interactions

## Tech Stack

- React
- TypeScript
- Vite
- Three.js
- `@react-three/fiber`
- `@react-three/drei`
- Lenis
- Framer Motion
- Lucide React

## Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
npm run preview
```

The production output is written to `dist`.

## Cloudflare Deployment

This is a normal Vite static SPA. Connect the GitHub repository to Cloudflare Pages with:

- Framework preset: `Vite`
- Build command: `npm run build`
- Build output directory: `dist`

Cloudflare Pages provides the SPA fallback for direct navigation to the client-side case-study paths. No Workers or server-side runtime are required. Deployment is performed manually by connecting the GitHub repository.

## Project Structure

```text
src/
  App.tsx       Main route-aware application and portfolio sections
  index.css     Global visual system and responsive styling
  main.tsx      React entry point
public/
  favicon.svg
  icons.svg
```

## Projects Featured

- ForceCore
- Nexus Sky
- ForceCore AI

## Environment Variables

No environment variables are required for the current static portfolio.

## Author

Ikram  
GitHub: https://github.com/NexusMC202

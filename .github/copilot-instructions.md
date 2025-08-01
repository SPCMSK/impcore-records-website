# Copilot Instructions for IMPCORE Label Website

<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

## Project Overview
This is a modern, minimalist website for an electronic music record label built with Next.js, TypeScript, and Tailwind CSS, inspired by mutual-rytm.com.

## Key Technologies
- **Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **CMS**: Sanity (headless CMS)
- **Deployment**: Vercel

## Design Guidelines
- **Dark aesthetic**: Primary background (#111111), white text (#F5F5F5), vibrant accents
- **Typography**: Sans-serif fonts (Inter), generous letter spacing for headings
- **Layout**: Minimalist, single-column design with generous whitespace
- **Responsive**: Mobile-first approach

## Component Structure
- Use TypeScript interfaces for all props
- Follow atomic design principles
- Implement reusable components in `src/components/`
- Use Server Components when possible for better performance

## Naming Conventions
- Components: PascalCase (e.g., `ReleaseCard.tsx`)
- Files: kebab-case for pages, PascalCase for components
- Variables: camelCase
- CSS classes: Tailwind utility classes

## Performance Requirements
- Optimize images with next/image
- Implement ISR (Incremental Static Regeneration)
- Maintain good Core Web Vitals scores
- Use proper loading states and error handling

## Music Player
- Global persistent music player
- Should continue playing across page navigation
- Use Zustand for state management

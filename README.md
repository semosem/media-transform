# Video Editor — Next.js + Cloudinary

A browser-based media editor built with **Next.js**, **TypeScript**, and **Cloudinary**.

The application lets users preview media, arrange clips on a timeline, apply Cloudinary transformations, and export the final result through a simple editing workflow.

## Live Demo

[Open the live application](https://prod-media-transform.vercel.app/)

## Features

- Upload and manage media assets
- Preview video and image files
- Timeline-based editing interface
- Add and arrange media clips
- Apply Cloudinary transformations
- Control playback and preview changes
- Export processed media
- Responsive browser-based interface
- Type-safe implementation with TypeScript

## Tech Stack

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Cloudinary](https://cloudinary.com/)
- CSS / PostCSS
- Vercel
- GitHub Actions

## Project Structure

```text
video-editor-nextjs/
├── app/                 # Next.js pages, layouts, and application routes
├── components/          # Editor, timeline, player, and UI components
├── hooks/               # Reusable React hooks
├── public/              # Static assets
├── .github/workflows/   # GitHub Actions deployment workflow
├── next.config.ts       # Next.js configuration
├── package.json
└── tsconfig.json

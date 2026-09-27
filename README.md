# JalSetu: Hyperlocal Flood & Damage Intelligence

A full-stack Next.js dashboard for Bihar flood mapping and hyperlocal disaster reporting.

## Features

- App Router architecture with Tailwind CSS
- Leaflet + React Leaflet map with severity-coded flood markers
- Community reporting form with optional GPS capture and image upload
- Offline-first queue for flood reports using localStorage
- Auto-sync when connectivity returns
- In-memory API seeded with Bihar flood samples near Sheohar / Bagmati

## Tech Stack

- Next.js 14 App Router
- TypeScript
- Tailwind CSS
- Leaflet
- React Leaflet
- Lucide React

## Getting Started

1. Install dependencies:
   npm install
2. Start the app in development mode:
   npm run dev
3. Open your browser at:
   http://localhost:3000

## Production Build

npm run build
npm run start

## Repo Notes

This project is intentionally built with an in-memory API for demonstration and local development. The flood points are centered around Sheohar, Bihar (26.5057, 85.2916).

# ForagePro

> Wild food at your doorstep

ForagePro is a premium subscription-based platform that connects experienced foragers with local businesses and restaurants, providing a reliable supply chain for wild ingredients. It focuses on building a network of trusted suppliers and buyers, ensuring high-quality products and promoting sustainable foraging practices. By targeting the B2B market, ForagePro aims to establish itself as a go-to platform for the culinary industry.

## Features

- Supplier network management
- Quality control and certification
- Marketplace for bulk wild ingredient orders

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Database:** Supabase (PostgreSQL)
- **Auth:** Supabase Auth
- **Styling:** Tailwind CSS
- **Language:** TypeScript

## Getting Started

1. Clone this repository
2. Copy `.env.example` to `.env.local` and fill in your credentials
3. Run `npm install`
4. Run `npm run dev`

## Project Structure

```
├── app/                  # Next.js App Router pages
├── components/           # React components
├── lib/                  # Utilities and helpers
├── supabase/            # Database schema
└── INSTRUCTIONS.md      # Detailed build guide for AI assistants
```

## Database

This project uses 3 main entities:
- **Idea**: User-generated ideas for wild food recipes, foraging techniques, or sustainable practices
- **User**: ForageHub users, including enthusiasts, experts, and suppliers
- **Recipe**: Wild food recipes shared by users

## Build Instructions

For detailed step-by-step build instructions, see [`INSTRUCTIONS.md`](./INSTRUCTIONS.md).

This file contains comprehensive guidance for building this project with AI coding assistants like Claude Code, Cursor, or Windsurf.

---

*Generated with [Claudery](https://claudery.io) - AI-powered blueprint generator*

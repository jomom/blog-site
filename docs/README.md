# Project Documentation

This directory contains the documentation for the Joel Momanyi Nyaosi (jmn.digital) personal portfolio and blog site.

## Architecture

- **Framework**: Astro
- **Styling**: Tailwind CSS
- **Content**: Markdown/MDX via Content Collections
- **Design System**: Sourced from Google Labs Stitch prototypes

## Layouts and Component Guidelines

- Keep pages clean and minimal.
- Use `src/layouts/BaseLayout.astro` for all top-level layout styling.
- Organize components:
  - `src/components/ui/` for small reusable elements.
  - `src/components/layout/` for structural components like navigation and footers.
  - `src/components/sections/` for layout blocks on single pages.

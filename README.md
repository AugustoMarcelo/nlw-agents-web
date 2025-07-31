# NLW Agents

This project, **NLW Agents**, was implemented during a Rocketseat event. It is a simple web application built with modern React tooling and best practices.

## Tech Stack

- **React** (with TypeScript)
- **Vite** (for fast development and build)
- **React Router DOM** (for routing)
- **@biomejs/biome** (for code formatting and linting)

## Project Structure

- `src/` — Main source code
  - `components/` — Reusable UI components
  - `lib/` — Utility functions
  - `pages/` — Application pages (e.g., `room.tsx`, `create-room.tsx`)
- `public/` — Static assets
- `index.html` — Main HTML file

## Patterns & Conventions

- Functional components with hooks
- TypeScript for type safety
- File-based organization for pages and components
- Utility functions in `lib/`

## Setup Instructions

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Start the development server:**
   ```bash
   npm run dev
   ```
3. **Build for production:**
   ```bash
   npm run build
   ```
4. **Preview production build:**
   ```bash
   npm run preview
   ```

## Configuration

- **Vite**: Configured via `vite.config.ts`.
- **TypeScript**: Configured via `tsconfig.json` and `tsconfig.app.json`.
- **Biome**: Formatting and linting via `biome.jsonc`.

---

Made with 💜 at Rocketseat's NLW event.

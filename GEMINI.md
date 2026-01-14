# GEMINI

## Project Identity
**Name**: Chef
**Description**: An AI App Builder that "knows backend". It creates full-stack web apps with built-in database, auth, and real-time capabilities.
**Base**: Forked from `bolt.diy`, built on `Convex`.

## Technology Stack
- **Languages**: TypeScript, JavaScript
- **Frontend Framework**: [Remix](https://remix.run/) (React)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Backend / Database**: [Convex](https://convex.dev/) (Real-time, reactive database)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **AI Integration**: [Vercel AI SDK](https://sdk.vercel.ai/)
- **Package Manager**: pnpm

## Repository Structure
- **`app/`**: Client-side code (Remix).
  - `routes/`: File-based routing.
  - `components/`: UI components.
  - `lib/`: Shared logic.
- **`convex/`**: Backend API and database schema.
  - `schema.ts`: Database definition.
  - `functions.ts`: Backend logic (queries, mutations).
- **`chef-agent/`**: The AI agent logic for generating apps.
- **`chefshot/`**: CLI tool for interacting with Chef.
- **`template/`**: Base template for new Chef projects.

## Development Workflow
### Setup
1. `pnpm install`
2. `pnpm run dev` (starts frontend)
3. `npx convex dev` (starts backend in parallel)

### Key Configuration
- `package.json`: Dependencies and scripts.
- `convex.json`: Convex configuration.
- `vite.config.ts`: Vite build settings.
- `tailwind.config.ts`: Styling configuration.

# SKILLS

## Convex Development
- **Schema**: Defined in `convex/schema.ts` using `defineSchema` and `defineTable`.
- **Functions**:
  - `query`: Read-only data fetching.
  - `mutation`: Write operations.
  - `action`: Third-party API calls (e.g., AI models).
- **React Integration**:
  - Use `useQuery` for reactive data fetching.
  - Use `useMutation` for triggering updates.
  - `convex/react` is the primary client library.

## Remix & Frontend
- **Routing**: File-based routing in `app/routes`.
- **Styling**: Use utility-first Tailwind CSS classes.
- **Components**: Reusable UI components in `app/components`.

## AI Agent (Chef)
- **Location**: `chef-agent/`.
- **Role**: Injects system prompts and handles the loop between user input and code generation.
- **Tools**: Uses Vercel AI SDK for model interactions.

## Best Practices
- **Type Safety**: Use TypeScript for all files.
- **Reactive Data**: Prefer Convex queries over manual `useEffect` fetching.
- **Tailwind**: Keep styles inline with utility classes; avoid custom CSS files where possible.

# Hello Hono

## Scope

Install and configure Hono with the `tsx` development server. Create a minimal Hono application and a single `/` route. Add a development script and preserve the existing TypeScript build.

## Feature outcome

The application serves plain text at `/`:

```text
AgentClinic is open for business
```

## Decisions

- Use Hono as the server framework, as required by the AgentClinic tech stack.
- Use `tsx` for local development.
- Render the route response as plain text; no layout or CSS work belongs in this phase.
- Keep the implementation small and focused on server startup and end-to-end TypeScript compilation.
- Preserve strict TypeScript settings and the existing `build` script unless setup requires a compatible adjustment.

## Context

This is roadmap Phase 1. It establishes the Hono foundation for later server-side JSX layouts, database-backed pages, and staff tools.

The mission is to create a welcoming, reliable service for agents and staff. The technical direction is an end-to-end TypeScript server using Hono and server-side rendering in later phases.

## Out of scope

- Shared layout components
- CSS
- SQLite or migrations
- Agent, ailment, therapy, appointment, or dashboard features
- Authentication, notifications, therapist profiles, or reporting

# Smart Farmer SVU

Smart Farmer SVU is a monorepo starter for the Smart Farmer platform. It includes the initial application setup for web, API, and mobile development using the same technology choices as the reference project, without the legacy Django codebase.

## Tech Stack

- `apps/web`: Next.js + React + TypeScript
- `apps/api`: NestJS + TypeScript
- `apps/expo`: Expo + React Native + TypeScript

## Project Structure

```text
smart-farmer-svu/
|-- apps/
|   |-- api/
|   |   |-- src/
|   |   |   `-- root/
|   |   |-- package.json
|   |   |-- tsconfig.build.json
|   |   `-- tsconfig.json
|   |-- expo/
|   |   |-- scripts/
|   |   |-- App.tsx
|   |   |-- app.json
|   |   |-- babel.config.js
|   |   |-- index.js
|   |   |-- package.json
|   |   `-- tsconfig.json
|   `-- web/
|       |-- src/
|       |   `-- app/
|       |-- next-env.d.ts
|       |-- next.config.mjs
|       |-- package.json
|       `-- tsconfig.json
|-- docs/
|   `-- local-development.md
|-- scripts/
|   `-- dev/
|-- .gitignore
|-- package.json
|-- package-lock.json
|-- README.md
`-- tsconfig.json
```

## Notes

- The workspace is managed from the repository root with npm workspaces.
- The current setup is intentionally minimal and focused on initial project bootstrapping.
- Legacy Django files are excluded from this project.

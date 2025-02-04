
### Apps and Packages

- `web`: Sample app
- `@repo/ui`: a stub ui component library shared by both `web` and `other` applications
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo
- `@repo/lib`: A library of utility functions shared across the monorepo

```
├── apps/
│   └── web/          # Next.js web application
├── packages/
│   ├── ui/           # Shared ui component library
│   ├── lib/          # Shared utility functions
│   ├── eslint-config/# Shared ESLint configurations
│   └── typescript-config/ # Shared TypeScript configurations
```

### Build

To build all apps and packages, run the following command:

```
pnpm build
```

### Develop

To develop all apps and packages, run the following command:

```
pnpm dev
```


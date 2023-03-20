# Typescript React.js Starter Kit

Non-opinionated TypeScript starter for React

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

## Features

- [x] ⚛️ React 18
- [x] ⛑ TypeScript
- [x] 📏 ESLint — To find and fix problems in your code
- [x] 💖 Prettier — Code Formatter for consistent style
- [x] 🐶 Husky — For running scripts before committing
- [x] 🚓 Commitlint — To make sure your commit messages follow the convention
- [x] 🚫 lint-staged — Run ESLint and Prettier against staged Git files

## Quick Start

The best way to start with this template

```sh
# pnpm
pnpm create next-app -e https://github.com/renatoxm/typescript-reactjs-starter
```

### Development

To start the project locally, run:

```sh
pnpm dev
```

Open `http://localhost:5173` with your browser to see the result.

## Documentation

### Requirements

- Node.js >= 12.22.0
- pnpm 7

### Directory Structure

- [`.github`](.github) — GitHub configuration including the CI workflow.<br>
- [`.husky`](.husky) — Husky configuration and hooks.<br>
- [`public`](./public) — Static assets such as robots.txt, images, and favicon.<br>
- [`src`](./src) — Application source code, including pages, components, styles.

### Scripts

- `pnpm dev` — Starts the application in development mode at `http://localhost:5173`.
- `pnpm build` — Creates an optimized production build of your application.
- `pnpm start` — Starts the application in production mode.
- `pnpm type-check` — Validate code using TypeScript compiler.
- `pnpm lint` — Runs ESLint for all files in the `src` directory.
- `pnpm format` — Runs Prettier for all files in the `src` directory.

### Path Mapping

TypeScript are pre-configured with custom path mappings. To import components or files, use the `@` prefix.

```tsx
import { Button } from '@/components/Button';

// To import images or other files from the public folder
import avatar from '@/public/avatar.png';
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more information.

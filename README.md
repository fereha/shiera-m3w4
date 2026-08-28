# vite-ts-starter

A reusable starter project built with Vite and TypeScript.

## Technologies

* Vite
* TypeScript
* ESLint
* Prettier
* Husky
* lint-staged
* GitHub Actions
* pnpm

## Setup

Clone the project:

```bash
git clone https://github.com/fereha/shiera-m3w4.git

```

Install dependencies:

```bash
pnpm install
```

Start the project:

```bash
pnpm dev
```

## Commands

```bash
pnpm dev
pnpm lint
pnpm typecheck
pnpm build
```

* `pnpm dev` — starts the development server
* `pnpm lint` — checks the code with ESLint
* `pnpm typecheck` — checks TypeScript errors
* `pnpm build` — creates the production build

## Git Hooks

Husky and lint-staged run ESLint and Prettier before commits.

## GitHub Actions

GitHub Actions runs automatically on every Pull Request.

It checks:

* ESLint
* TypeScript typecheck

## Version

**v0.1**

Initial Vite + TypeScript starter setup.

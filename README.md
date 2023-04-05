# Modified Turborepo starter updated with Yarn Berry zero-installs

**Note:** This is **NOT** an official Turborepo starter, refer to https://github.com/vercel/turbo for the official ones.

## Modifications

This modified Turborepo uses the newer [yarn berry with zero-installs](https://yarnpkg.com/features/zero-installs) for package management. The TypeScript config has also been pre-configured to work with VS Code, but you'll need to manually tell VS Code how to recognize the TypeScript version, as follows:

### Update VS Code to use the workspace TypeScript version

- In VS Code, in a TypeScript file, press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>p</kbd>
- Choose `Select TypeScript Version`
- Pick `Use Workspace Version`

## What's inside?

The repo includes the following packages/apps:

### Apps and Packages

- `docs`: a [Next.js](https://nextjs.org/) app
- `web`: another [Next.js](https://nextjs.org/) app
- `ui`: a stub React component library shared by both `web` and `docs` applications
- `eslint-config-custom`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

## Setup

To use this repo, simply fork & clone as usual,
or download it using degit to start with no git history:

```sh
npx degit mlaposta/turborepo-yarn-zero-installs turborepo-yarn-zi
cd turborepo-yarn-zi
yarn
git init . && git add . && git commit -m "Init"
```

### Build

To build all apps and packages, run the following command:

```
cd turborepo-yarn-zi
yarn build
```

### Develop

To develop all apps and packages, run the following command:

```
cd turborepo-yarn-zi
yarn dev
```

### Further info

Refer to the official [Turborepo github](https://github.com/vercel/turbo) for the full documentation.

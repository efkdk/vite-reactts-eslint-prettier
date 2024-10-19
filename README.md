# Vite Template - React + TypeScript + ESLint + Prettier

This is a starter template for building a modern React application using Vite, with TypeScript, ESLint, and Prettier pre-configured for a great developer experience.

## Features

- ⚡️ [Vite](https://vite.dev/) — Lightning-fast bundling and development server.
- ⚛️ [React](https://react.dev/) — A popular JavaScript library for building user interfaces.
- 🛠 [TypeScript](https://www.typescriptlang.org/) — Strongly typed JavaScript for better tooling and error checking.
- 📏 [ESLint](https://eslint.org/) — Linting to maintain code quality and consistency.
- 🎨 [Prettier](https://prettier.io/) — Code formatter to automatically enforce consistent style.

## Getting Started

### Prerequisites

Ensure you have the following tools installed:

- [Node.js](https://nodejs.org/) (v14+)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

Clone repo and run 
```bash
npm install
```
or
```bash
yarn install
```
## Start

Run 
```bash
npm run dev
```
or
```bash
yarn dev
```
## Steps in VS Code

(works better with this template)
1. Install Eslint and prettier extension for vs code.
2. Make sure both are enabled
3. Make sure all packages are Installed. (Mostly Eslint and prettier in node_modules)
4. Enable formatOnSave for vs code
```json
{
  "eslint.enable": true,
  "eslint.run": "onType",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "editor.formatOnSave": true
}
```
5. Open a .tsx file and check if the bottom right corners of vs code have Eslint and Prettier with a double tick
### Happy coding :)

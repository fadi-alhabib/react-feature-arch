# Grodd CLI 🦍

## Introduction

**Grodd CLI** is a powerful command-line tool that helps you quickly set up a React + TypeScript project with Chakra UI, Axios, Jotai, and React Router. It also allows you to generate feature modules efficiently. This CLI is designed to streamline your development process and keep your code organized.

## Features

- 🏗 **Initialize a new React + TypeScript project** with all essential dependencies.
- ⚡ **Pre-configured Chakra UI setup** for a seamless UI experience.
- 🛠 **Easily create feature modules** with the necessary folder structure.
- 🚀 **Optimized TypeScript configuration** for better developer experience.
- 🦧 Fun and engaging CLI messages!

## Installation

To use Grodd CLI, install it globally via npm:

```sh
npm install -g grodd-cli
```

## Usage

### 1. Initialize a New Project

Create a new React + TypeScript project with Chakra UI and other essential dependencies:

```sh
grodd init my-app
```

_This will:_

- Create a Vite-powered React + TypeScript project.
- Install `@chakra-ui/react`, `axios`, `jotai`, `react-router-dom`, and other dependencies.
- Set up Chakra UI in `main.tsx`.
- Configure TypeScript paths in `tsconfig.app.json`.
- Set up `vite.config.ts` with tsconfig paths support.
- Display a cool gorilla ASCII art!

#### After installation:

```sh
cd my-app
npm run dev
```

### 2. Create a Feature Module

To generate a new feature module with the required structure, run:

```sh
grodd cf feature-name
```

_This will:_

- Create a `features/feature-name` folder inside `src`.
- Generate subfolders: `components`, `hooks`, and `services`.
- Create a `store.ts` file with a Jotai atom.
- Create a `feature-namePage.tsx` component.
- Generate an `index.ts` file for easy imports.

## Example

```sh
grodd init jungle-app
cd jungle-app
grodd cf dashboard
```

This will create a project named `jungle-app` and a new feature module `dashboard` inside `src/features/`.

## Notes

> "Keep Your code clean or something bad will happen 🥷"

## Author

🦍 **Fadi Bassam Alhabib**

## License

MIT License

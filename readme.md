# TypeScript Hello World Project

A simple TypeScript project that demonstrates the basic setup and configuration.

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```

## Available Scripts

- **Build the project**:
  ```
  npm run build
  ```

- **Run the compiled JavaScript**:
  ```
  npm start
  ```

- **Build and Run the compiled JavaScript**:
  ```
  npm run build && npm start
  ```

- **Run with ts-node (without compiling)**:
  ```
  npm run dev
  ```

## Project Structure

```
ts-demo-4-admin/
├── src/
│   └── index.ts       # Main TypeScript file
├── dist/              # Compiled JavaScript (generated after build)
├── package.json       # Project dependencies and scripts
├── tsconfig.json      # TypeScript configuration
├── .gitignore         # Git ignore file
└── readme.md          # This file
```

## Next Steps

- Add more TypeScript files in the `src` directory
- Install additional dependencies as needed
- Configure testing with Jest or Mocha
- Set up linting with ESLint

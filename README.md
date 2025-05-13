# Workflow - Study Task 1

## Description

A simple project that demonstrates how to fetch and display data from a public API using modern frontend tooling.

This project was created as part of Study Task 1, and it applies the core concepts of Git, GitHub, API interaction, and development environment setup. It includes configurations for Vite, environment variables, and GitHub Actions for deployment.

## Technologies Used

- HTML, JavaScript
- Vite
- (JSONPlaceholder API)[https://jsonplaceholder.typicode.com)]
- ESLint
- Prettier
- Vitetest
- Git & GitHub
- GitHub Actions

## Npm Scripts

- **dev** = Start the Vite development server
- **lint** = Run ESLint checks
- **format** = Format code with Prettier
- **test** = Run unit tests

## Project Setup

To view this project locally, you can clone the repository:

```bash
git clone https://github.com/Mayamariaruth/workflow-task1
```

1. Install the dependencies:

```bash
npm install
```

2. Run the development server (for Vite):

```bash
npm run dev
```

3. Run Eslint:

```bash
npm run lint
```

4. Format code with Prettier:

```bash
npm run format
```

5. Run unit tests:

```bash
npm run test
```

## Environment Variables (Vite only)

Create a .env file with the following:

```bash
VITE_API_URL=https://jsonplaceholder.typicode.com/posts
```

Use it in your code like this:

```bash
const url = import.meta.env.VITE_API_URL;
```

## Author

**GitHub Username** = (Mayamariaruth)[https://github.com/Mayamariaruth]

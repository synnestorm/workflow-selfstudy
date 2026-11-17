# Workflow Self-Study

This repository is a lesson for my course on workflow. This is only for practice.

## Description

In this repository I will create a small project that:

- Uses Git, GitHub, branches, and pull requests.
- Uses README.md with proper Markdown.
- Uses npm, installs dependencies, and sets up scripts.
- Uses ESlint and Prettier with config files.
- (Optional) Uses .env variables via Vite.
- (Optional) Uses GitHub Actions to deploy.

## Technologies used

- HTML5
- Vanilla JavaScript
- CSS3
- Vite
- ESLint
- Prettier
- npm

## Getting Started

### Installing

1. Clone the repo:

```bash
git clone git@github.com:synnestorm/workflow-selfstudy.git
```

2. Install the dependencies:

```
npm install
```

### npm Scripts

Available npm scripts:

```bash
npm run dev
npm run lint
npm test
```

## Environment Variables

This project uses environment variables to store configuration.

1. Create a `.env` file in the project root.
2. Add the following variable:

```env
VITE_API_URL=https://jsonplaceholder.typicode.com/posts
```

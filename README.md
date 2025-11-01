# George Pearse · Project Notebook

This is the user site for https://georgepearse.github.io - a Vite + React application that documents projects, experiments, and research areas.

The homepage presents a card for every public repository on the [GitHub profile](https://github.com/GeorgePearse), enriched with tags for easy filtering by topic.

## About

A living notebook: whenever diving into a new area of technology, the process starts by building something and tracking where it becomes difficult. Those lessons surface here.

## Features

- Real-time GitHub repository cards fetched from GitHub API
- Topic-based filtering (Computer Vision, LLMs, MLOps, etc.)
- Direct links to repository documentation
- Fully responsive React + TypeScript application
- Automated testing with Playwright
- Code quality checks with oxlint, ESLint, and Prettier

## Running Locally

```bash
npm install
npm run dev
```

## Testing

```bash
npm test              # Run Playwright tests
npm test:ui          # Run tests in UI mode
npm run lint         # Run oxlint
npm run format       # Format with Prettier
```

## Build & Deploy

```bash
npm run build        # Build for production
npm run preview      # Preview production build
```

Deployments are automated via GitHub Actions on push to main.

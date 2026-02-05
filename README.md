# ADA Demo Project

A minimal TypeScript project demonstrating [ADA (Autonomous Dev Agents)](https://github.com/ishan190425/autonomous-dev-agents) — autonomous AI dev teams for any repo.

## About

This is a demo project used to showcase how ADA bootstraps and manages autonomous development teams. It starts as a simple TypeScript project and becomes an AI-managed codebase after running `ada init`.

## Quick Start

```bash
# Clone this repo
git clone https://github.com/ishan190425/ada-demo-project.git
cd ada-demo-project

# Install dependencies
npm install

# Build
npm run build

# Run
npm start
```

## Using with ADA

After installing the ADA CLI:

```bash
# Initialize an autonomous dev team
ada init

# Check team status
ada status

# Run a dispatch cycle
ada run
```

## Structure

```
ada-demo-project/
├── package.json          # npm configuration
├── src/
│   └── index.ts          # Application entry point
├── tsconfig.json         # TypeScript configuration
├── .gitignore
└── README.md
```

After `ada init`, an `agents/` directory will be created with:
- Team roster and rotation state
- Shared memory bank
- Role playbooks
- Dispatch protocol

## License

MIT
